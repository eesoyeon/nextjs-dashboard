## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

<br>

# Acme Dashboard

Next.js 공식문서 튜토리얼로 만든 송장 관리 앱입니다.

<img src='./images/스크린샷 2024-12-03 오후 4.53.48.png' width='400'>

## Login

주어진 이메일과 비밀번호로 로그인이 가능합니다.

```
Email: user@nextmail.com
Password: 123456
```

<img src='./images/스크린샷 2024-12-03 오후 5.20.13.png' width='300'>

## Home

모든 송장 정보와 수익을 시각화한 페이지

-  `Dashboard`: 총 송장 정보
-  `Recent Revenue`: 최근 12달의 수익 그래프
-  `Latest Invoices`: 날짜별로 정렬된 최신 5개의 송장

<img src='./images/스크린샷 2024-12-03 오후 4.59.52.png' width='700'>

## Invoices

고객들의 송장 정보를 나타내는 페이지

송장을 추가, 수정, 삭제하는 기능이 있고 검색과 페이지네이션이 가능합니다.

<img src='./images/스크린샷 2024-12-03 오후 5.06.20.png' width='500'>

### 1. Create

고객, 송장 금액, 상태를 입력할 수 있고, 폼의 데이터가 유효하지 않으면 에러가 발생합니다.

<img src='./images/스크린샷 2024-12-03 오후 5.03.01.png' width='500'>

<img src='./images/스크린샷 2024-12-03 오후 5.03.13.png' width='500'>

### 2. Edit

수정하는 송장 금액이 0보다 작으면 에러가 발생합니다.

<img src='/images/스크린샷 2024-12-03 오후 5.03.24.png' width='500'>

<img src='/images/스크린샷 2024-12-03 오후 5.05.34.png' width='500'>
