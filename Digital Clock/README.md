## 디지털 시계를 만들었습니다

## 코드 설명

우선 .container에 text-align 태그를 center로 주어서 출력될 시간을 중간에 오게 하였습니다

또한 .clock에 width,margin을 주어 크기를 조정해주었습니다 

또한 border속성으로 테두리 색도 바꿨습니다


![image](https://user-images.githubusercontent.com/97486300/174728330-a3a47577-8cf8-48c4-85f0-dd2ac4b3d7f9.png)

## div 태그

div태그로 class를 선언, 각각 위에서 선언했던 .container과 .clock를 div에 적용시킵니다<br>
또한 시작과 정지 버튼을 만들어줍니다

![image](https://user-images.githubusercontent.com/97486300/174729281-afbbf828-6089-486a-a95c-012a9b47bc47.png)



## 스크립트 부분입니다

var 태그로 시간이 표시될 h1 부분,<br>
시작 버튼과 정지 버튼을 넣을거라는걸 입력합니다 <br>

![image](https://user-images.githubusercontent.com/97486300/174728790-fbac1119-bd7f-4d2e-977f-95a341dea13c.png)

## 함수 적용

1.date 함수를 선언합니다 date 함수로 현재 시간을 불러옵니다<br>
2.hour 함수를 선언합니다 date.getHours를 써주어 현재 시간을 불러옵니다<br>
3.minutes 함수를 선언합니다 date.getMinutes를 써주면 현재 분을 가져옵니다<br>
4.seconds 함수를 선언합니다 date.getSeconds는 현재 초를 가져옵니다<br>
5. time 함수에 `${hour}:${minutes}:${seconds}` 를 써줍니다 <br> 
   이걸 써줌으로 현재 시간,분,초가 흘러갑니다 <br>

![image](https://user-images.githubusercontent.com/97486300/174729190-b98a4213-4d59-495a-9608-9aded1981a5e.png)

## 시작,정지 버튼 적용

이제 시작 버튼과 정지 버튼을 만들어줍니다<br>
시작 버튼은 클릭시 getTime 1000으로 설정되게 해줍니다

정지 버튼은 클릭시 0으로 설정해 시계가 멈추게 해줍니다<br>
![image](https://user-images.githubusercontent.com/97486300/174730646-91d2ceed-e573-4a51-85ac-2593fed479a5.png)

## 실행화면

초기화면입니다<br>

![image](https://user-images.githubusercontent.com/97486300/174731058-011814a6-57ec-416b-a25a-15fc49281868.png)

여기서 시작버튼을 누르면<br>

![image](https://user-images.githubusercontent.com/97486300/174731180-f3295b53-d2dc-46a5-9973-3132b9ddf0c5.png)

이렇게 현재 시간이 초까지 정확하게 나옵니다<br>

이번엔 정지버튼을 눌러보겠습니다

![image](https://user-images.githubusercontent.com/97486300/174731314-27aa1486-5d92-4965-9453-dcb3cf05ddd3.png)

이렇게 시간이 멈추게 됩니다

여기서 다시 시작버튼을 누르면

![image](https://user-images.githubusercontent.com/97486300/174731658-c8b92559-7ada-4215-b60d-025269c2ac8c.png)

이런식으로 다시 시작버튼을 누른 시간 기준으로 다시 흘러가게 됩니다

## 이상 디지털 시계 만들기였습니다

