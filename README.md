# daily_note

### 02/24(수)

- selectKey 란
VO에 no와 name을 세팅하고 param객체에 담아서 Service단을 거쳐 Mapper로 전달합니다.   
그리고 order="BEFORE", no를 select문을 통해 조회하고 selectKey 안의 keyProfperty = no에 바로 저장합니다.     
그럼, 저장된 no를 바로 아래의 insert문에서 사용할 수 있습니다.
   
출처: https://backstreet-programmer.tistory.com/100 [글쓰는 개발자]   

- 오늘의 공부 https://kr.vuejs.org/v2/guide/forms.html

