 
# 안드로이드 스튜디오를 이용하여 전화번호부 앱을 만들기
[![image](https://img.shields.io/badge/Build-Gradle%205.1.1-yellowgreen)](https://gradle.org/) 
[![image](https://img.shields.io/badge/Android%20SDK-API%2029%3A%20Android%209.%2B-brightgreen) ](https://developer.android.com/studio/?gclid=CjwKCAjwh7H7BRBBEiwAPXjadjupXKrLjEJYAGBpFkUAfz0EV5_K5790QOU1YjOq933gNe1xoCs6IhoCKXQQAvD_BwE&gclsrc=aw.ds)
[![image](https://img.shields.io/badge/Language-Java-orange)](https://www.java.com/ko/)




# 화면설명

## :memo: 첫번째 화면


![image](https://user-images.githubusercontent.com/42762236/94188797-d9e6c680-fee4-11ea-8d9e-a2f1dbcac173.png)


```
- “ADD CONTACT” 버튼을 누르면 <2번째 화면> 으로 이동
- 핸드폰 자체 “뒤로가기” 버튼 작동 안함
- “EXIT” 버튼을 누르면 앱 종료를 물어보는 AlertDialog창이 뜸
- “YES, EXIT” 선택 시 종료, “NO, CANCEL” 선택 시 창으로 다시 돌아감
```



## :memo: 두번째 화면
![image](https://user-images.githubusercontent.com/42762236/94189509-cc7e0c00-fee5-11ea-93d8-50dee6ad451f.png)



```
- 이름, 성별, 전화번호 정보를 입력 가능
- 처음에 성별은 unspecified로 선택되어 있음
- Male 선택 시 초록색 프로파일 사진으로 변경
- Female 선택 시 주황색 프로파일 사진으로 변경
- Unspecified 선택 시 검정색 프로파일 사진으로 변경
- 프로파일 사진 정보는 다음 장에 있음
- ”SAVE” 버튼 선택 시 1번 화면에 이름, 성별 프로파일 사진 전화번호, “전화걸기” 버튼이 있는 칸이 추가됨
- ”SAVE” 버튼 선택 시 이름, 전화번호에 입력된 값이 없으면 칸이 추가되지 않음
- ”CANCEL” 버튼 선택 시도 칸이 추가되지 않음
- ”뒤로가기” 버튼 작동 안함
```          
         
         

    
      
![image](https://user-images.githubusercontent.com/42762236/94189804-30083980-fee6-11ea-8f02-dc399e7e662e.png)

- Gender가 Unspecified이면 1번 검정색 프로파일을 보여줌
- Gender가 Female이면 2번 주황색 프로파일 사진을 보여줌
- Gender가 Male이면 3번 검정색 프로파일 사진을 보여줌



## :memo: 세번째 화면

![image](https://user-images.githubusercontent.com/42762236/94190664-609ca300-fee7-11ea-8a88-0de019c30a7b.png)


```
- 두번째 화면에서 정보 입력뒤 save 버튼을 누르면 첫번째 화면에 Person 전화번호부가 추가 된다
- 화면이 꽉차면 스크롤뷰로 내릴수 있다

```     



![image](https://user-images.githubusercontent.com/42762236/94190885-ad807980-fee7-11ea-98ca-7bc409e619d5.png)

- Call 버튼을 누르면 전화거는 화면으로 이동




## :books: 전체적인 설계 종합도 

![image](https://user-images.githubusercontent.com/42762236/94191060-ef112480-fee7-11ea-98da-e5bdfabd2c01.png)





## :mailbox_with_mail: Connect

```

  Github : https://github.com/Youngminah
  Email : bluebelsmudi@gmail.com
  
```






