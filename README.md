## 페이프로그래밍 실습

### 결과물

![](/2022-10-07.gif)

## 구현 내용

- imgField를 사용해서 이미지 첨부 가능하게 끔 구현
- html에서 {% if %} 구문을 사용해서 만약 이미지 파일이 없다면 안보이게끔 설정
- 수정시 created_at을 order_by 역순으로 출력
- Django의 date 형식을 2022-10-07 형식으로 변환
- timesince를 통해 14분전 처럼 보이게끔 구현
- 수정하면 몇분전이 0으로 되게끔 저장된 DB에서 create_at이 아닌 updated_at을 끌고 오게끔 변경
- truncatewords을 통해서 본문에 단어 수가 많아지면 ...으로 구현
- 프론트는 부트스트랩과 CSS를 적용
