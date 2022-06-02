# sunggyu

## 업무개발
기존에는 상담원에게 전화상담으로 주문을 취소했으나, 주말 및 공휴일에 응대가 늦어짐
일시불 결제 취소 개발하여 업무 간편화
-> 결제 취소 시, 출고확정 이전이라면 즉시환불, 이후라면 상담원에 접수되어 유선 처리

## 인프라
로컬에서 maven build 및 filezilla로 수작업하여 배포하였던 것을
svn, jenkins로 CI/CD 구축
https://escapefromcoding.tistory.com/695

## 북클럽 스터디
실용주의 프로그래머 TOPIC 30~40 중 1개 주제를 정해서 한주동안 실천하고 글 남기기
https://escapefromcoding.tistory.com/696

- 일시불 결제 취소 개발
- 배송지 저장/조회 개발
- 광고 노출 기간 설정 기능 개발(admin 페이지 연동)
- 상품 가격 변경 설정 기능 개발(admin 페이지 연동)
- 이벤트 응모 및 당첨자 알림톡 발송 개발(admin 페이지 연동)
- 배송현황 자동 업데이트 개발

### CI /CD

- [svn, jenkins를 이용하여 CI/CD 구축](https://escapefromcoding.tistory.com/695)

### confluence 활용

- 개발 내용 문서로 작성하여 공유(ex. 네이버 EP 연동)
- 개발환경 셋팅 방법, 각종 url 정리하여 공유
