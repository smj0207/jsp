## jsp정리입니다

jsp 코드 표기법

<%@	%> : 지시문 >> JSP 페이지 속성 지정

<%	%> : 스크립트릿 >> 가장 많이 쓰임. 자바 코드 블록, 변수(지역) 선언만 가능

<%!	%> : 선언문 >> 전역변수 혹은 메소드 선언

<%=	%> : 표현식 >> 웹 브라우저에 직접 결과 값을 출력

<%-- 주석 --%> : 여러 줄의 주석

// : 한 줄 짜리 주석

<jsp:action>	</jsp:acton> : 액션 태그 >> 다른 페이지를 포함 혹은 이동을 명령

## ⅰ.1번째 코드입니다


![image](https://user-images.githubusercontent.com/97486300/170396073-bb8bf447-b383-4438-a9d9-73ee4842cd16.png)

![image](https://user-images.githubusercontent.com/97486300/170395953-244cd3f2-9ab4-4cec-a842-87f271a2723c.png)
  
##  1회차로는 전역변수와 지역변수에 대해 배웠습니다
  
  ![image](https://user-images.githubusercontent.com/97486300/170396166-30f7035e-b214-4412-8fdd-10c1acf8feea.png)
  
  전역변수는 이런식으로 새로고침 할때마다 1씩 추가되는 반면 지역변수는 그대로입니다
  
  지역변수는 메인 함수 내에서만 사용 가능합니다 하지만 전역변수는 코드내에서라면 어느 지역에서나 사용이 가능합니다
  
  
 ## ⅱ.2번째 코드입니다
  
  ![image](https://user-images.githubusercontent.com/97486300/170396765-bce05d06-3eca-4605-b1ce-fcdbbe1366b6.png)
  ![image](https://user-images.githubusercontent.com/97486300/170396819-168db7e5-a900-4913-8398-9b8ea576ae86.png)
  
  변수와 연산자, 스크립트릿을 사용하여 코드를 만들었습니다
  ![image](https://user-images.githubusercontent.com/97486300/170397058-c21c4627-b369-45c9-9bfe-f3212690b13c.png)
  실행 결과 입니다 첫 실행에선 뺄셈이,
  ![image](https://user-images.githubusercontent.com/97486300/170397153-82f83ca0-0765-4015-bf6f-3a97aefdeec6.png)
  두번째 실행에선 덧셈이 실행됩니다
  
  
 ## ⅲ.3번째 코드입니다
  ![image](https://user-images.githubusercontent.com/97486300/170397562-8e486673-566e-40b3-95c7-67cb9329fba4.png)
  ![image](https://user-images.githubusercontent.com/97486300/170397613-8a6a29af-b375-4cc4-aafe-1350663b625e.png)
  
  1차원 배열로 성적처리를 하는 프로그램입니다
  
  ![image](https://user-images.githubusercontent.com/97486300/170397811-38a6d090-9c75-425c-ac0c-79bd9f2b0ff2.png)
  
  실행결과 입니다 총합 점수는 물론 average 함수를 이용해 평균도 구했습니다
  
##  ⅳ.4번째 코드입니다
  ![image](https://user-images.githubusercontent.com/97486300/170397981-041452ce-1b79-4cb4-9c3f-e1b01d26abcf.png)
  ![image](https://user-images.githubusercontent.com/97486300/170398110-c6021754-b5e1-42d2-a7c8-a71c5bf58e2d.png)
  
  2차원 배열로 성적을 구하는 코드입니다
  
  ![image](https://user-images.githubusercontent.com/97486300/170398230-cafd83ad-0a3e-42e3-be01-41841b49aaee.png)
  
  실행결과 입니다
  
##  아래 코드는 2차원 배열을 이용한 다른 성적처리 코드입니다
  ![image](https://user-images.githubusercontent.com/97486300/170398560-f541394f-7c7b-4161-86a8-68e7e2a0bd2c.png)
  ![image](https://user-images.githubusercontent.com/97486300/170398657-ca351de8-10af-4896-9638-554387c5b319.png)
  
  실행결과 입니다
  
  ![image](https://user-images.githubusercontent.com/97486300/170398729-7470db67-8e8a-4618-83c2-08976ee18007.png)
 
 테이블 태그를 이용해 시각적인 비쥬얼 업그레이드를 한 모습을 볼 수 있습니다

## ⅴ.5번째 코드는 클래스와 메소드를 사용해 은행 출금 프로그램을 만들었습니다


 ![image](https://user-images.githubusercontent.com/97486300/170398900-dcd25128-ff57-4e48-979a-1132d6fac3d0.png)
 ![image](https://user-images.githubusercontent.com/97486300/170399075-8bc4855a-fdf1-47a1-aac0-5af087d079fc.png)
 ![image](https://user-images.githubusercontent.com/97486300/170399119-1a46db2a-41d6-41a9-b0fd-2a7bbc1d7e32.png)
 
 Account 클래스를 만들어 사용한 모습입니다 
 아래는 실행 결과입니다
 
 ![image](https://user-images.githubusercontent.com/97486300/170399313-61fce3dd-0c14-45ed-8799-4bc60f8d1cda.png)
 
## ⅵ.6번째 코드는 if else문을 사용한 코드입니다

![image](https://user-images.githubusercontent.com/97486300/170400832-3daae075-d28a-4108-8833-cb28d609251b.png)
![image](https://user-images.githubusercontent.com/97486300/170400910-d6ba85b9-ae7c-460d-8dd3-467314eaae4a.png)

사용자 아이디와비밀번호, 로그인 아이디와비밀번호 를 이용한 로그인 페이지 입니다 

우선 사용자 아이디,비밀번호와 로그인 아이디 비밀번호가 일치하지 않을때는 

![image](https://user-images.githubusercontent.com/97486300/170401117-46fdd117-ca12-4faf-9102-c1e96e27741d.png)

이런식으로 ㅠㅠ라는 모음이 나오면서 로그인이 실패했다는 걸 알립니다 하지만

![image](https://user-images.githubusercontent.com/97486300/170401234-9f732fcf-302b-4460-8940-420a38300b31.png)

이 부분, String login_id에 admin1을 admin으로 바꿔서 실행해 보면

![image](https://user-images.githubusercontent.com/97486300/170401324-716c0644-4831-468f-a460-1e0480a16a4d.png)

## 실행

![image](https://user-images.githubusercontent.com/97486300/170401407-f5d92f8d-c927-4c2b-9f1b-5d9f16bcb2f4.png)

이런식으로 로그인이 된 모습을 볼 수 있습니다

이상 jsp 기초공부였습니다 @@
