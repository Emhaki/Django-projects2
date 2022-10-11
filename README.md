# Django-projects2

## 구현한 프로젝트 

![2022-10-07](https://user-images.githubusercontent.com/105331868/194591688-a3d2b185-2a99-4565-bd5c-674b502bf065.gif)

## 🔎 구현 기술

- imgFelid를 사용해서 이미지 파일을 첨부할 수 있게끔 구현 ( imgfile = models.ImageField(null=True, upload_to="", blank=True))   
- Django bootstrap을 통해 form 양식 간소화   
- 폼에 csrf 토큰을 추가해서 유효성 검증   
- 평점 부분의 grade에 default 값을 1로 설정하고 minValue와 MaxValue를 0 ~ 5로 설정   
- 게시물 생성 시간인 create와 수정 시간인 update에 DateTimeField를 추가했고, 데이터베이스를 이용해 views.py에서 get과 pk 값을 통해 order_by순으로 정렬   
- timesince를 통해서 게시물이 몇분전에 작성됐는지 보이게끔 구현   
- date를 "Y-m-d"로 가시성 있게 변경   
- {% if %} 구문을 통해 만약 {% review.imgfile %}이 있으면 div를 보여주고 없으면 안보여지게 끔 구현   
