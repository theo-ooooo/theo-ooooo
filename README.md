# 강경원 · Backend Engineer

운영에서 버티는 서비스를 만듭니다. 성능 병목은 구조로 풉니다.
기획부터 배포까지 직접 굴리는 사이드 프로젝트로 새 스택을 검증합니다.

[kwkang.net](https://kwkang.net) · [kkwondev@gmail.com](mailto:kkwondev@gmail.com)

---

## 지금 만드는 것

<table>
<tr>
<td width="50%" valign="top">

<a href="https://jangteojigi.com"><img src="https://raw.githubusercontent.com/theo-ooooo/theo-ooooo/main/assets/jangteojigi.png" alt="장터지기" /></a>

### 🏛️ [장터지기](https://jangteojigi.com)
**나라장터 입찰공고 알림**

평일 하루 1,095건 올라오는 조달청 공고 중 **우리 회사가 나갈 수 있는 것만** 골라 알려줍니다. 실제 관납업체(피복·방탄 제조)에 붙여 쓰면서 만듭니다.

- 조달청 OpenAPI 30분 주기 수집 — 누적 공고·낙찰 각 **17만 건**
- 지역제한·직생증명·업종 대조 → `가능 / 검토 / 불가` 자동 판정
- 지역제한이 API에 안 담겨(개찰 전 6,978건 중 **0건**) PDF·HWP·HWPX 첨부를 직접 파싱
- 과거 낙찰률 중앙값·낙찰하한율로 **예상 낙찰 구간** 산출
- 한국어 오탐(`방검`→지**방검**찰청) 낱말 가장자리 규칙으로 **87% 제거**

`Spring Boot 3.4` `Java 17` `QueryDSL` `Next.js 16` `PostgreSQL` `Cloud Run`

</td>
<td width="50%" valign="top">

<a href="https://backtick.blog"><img src="https://raw.githubusercontent.com/theo-ooooo/theo-ooooo/main/assets/backtick.png" alt="백틱" /></a>

### 📝 [백틱](https://backtick.blog)
**개발자 블로그 플랫폼**

누구나 가입해 `/@handle` 블로그를 갖는 멀티유저 플랫폼 + **국내 기업 기술블로그 큐레이션 피드**.

- 마크다운 발행, 태그, 컬렉션(시리즈), 개인 블로그 홈
- 우아한형제들·카카오·토스·네이버 D2·GeekNews·velog RSS 주기 수집
- 글 없는 새 플랫폼의 **콜드스타트를 외부 콘텐츠 수급으로** 해결
- AI 3줄 요약, 팀 페이지, 검색·북마크·통계
- App Router SSR + OG·sitemap + IndexNow(빙·네이버 즉시 색인)

`Next.js 16` `React 19` `Prisma` `NextAuth v5` `PostgreSQL` `Vercel`

</td>
</tr>
</table>

---

## 스택

| | |
|---|---|
| **Backend** | Java · Spring Boot · Kotlin · Node.js · NestJS · Python |
| **Frontend** | TypeScript · React · Next.js · Tailwind · Flutter |
| **Data** | PostgreSQL · MySQL · Redis · JPA/QueryDSL · Prisma |
| **Infra** | Docker · GCP(Cloud Run, Scheduler) · AWS(ECS/ECR) · GitHub Actions |

## 지난 프로젝트

| | | |
|---|---|---|
| **Lunatalk** | 전자상거래 — 상품/주문/결제 API, Redis 캐시로 조회 성능 개선, CRA→Next.js 마이그레이션 | `Spring Boot` `Next.js` `Redis` |
| **Tech Blog** | [kwkang.net](https://kwkang.net) — SSR 블로그, 다크모드·태그·댓글 | `Next.js` `TypeScript` |

---

<details>
<summary><b>어떤 개발자인가</b></summary>

<br />

글로벌 서비스 환경에서 플랫폼 기능을 개발하고, 운영 중 발생하는 성능 이슈를 구조적으로 해결해 온 백엔드 개발자입니다.

Node.js(NestJS) 기반 실무 경험을 중심으로 결제·이벤트·관리자 시스템·운영 자동화를 직접 설계·구현했고, 슬로우 쿼리 개선과 API 구조 리팩토링으로 실제 서비스 응답 성능과 안정성을 끌어올렸습니다.

프론트엔드(React, Next.js) 경험이 있어 기획·디자인과 협업할 때 전체 흐름을 보고 문제를 풉니다. 최근에는 Spring Boot·Kotlin·클라우드(GCP/AWS)로 넓혀 더 큰 규모의 시스템 설계를 연습하고 있습니다.

</details>

<details>
<summary><b>중요하게 생각하는 것</b></summary>

<br />

- **운영을 전제로 설계한다** — 장애 때 어디를 볼지 정해두지 않은 구조는 미완성이라고 봅니다
- **병목은 구조에서 찾는다** — 쿼리 하나를 고치기 전에 데이터 흐름을 먼저 그립니다
- **측정한 것만 말한다** — "빨라졌다"보다 "2.5배 빨라졌다"를 씁니다
- **읽는 사람을 위해 쓴다** — 코드도 커밋 메시지도 다음 사람이 읽습니다

</details>
