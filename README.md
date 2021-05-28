# Django Basic Apps
## 링크 : http://3.36.128.159:8000/

### User,Database 에 대한 Create,Update,Delete,Read 구현
### ● Framework : Django,Bootstrap 
### ● Amazon S3 , RDS (MySQL) 활용,EC2 로 배포

#### ● 실행방법 
        1. 다운로드후  python manage.py runserver
        2. 127.0.0.1:8000 접속

<img src="/Results/home.png">    


## 1. Bookmark 
        - Bookmark - link 1대1 관계    
<img src="/Results/Bookmark_List.png">  
<img src="/Results/Bookmark_Detail.png">  

## 2. Photo 
        - Album , Photo 1:N 관계 
<img src="/Results/Photo_List.png">  
<img src="/Results/Album_Detail.png">  

## 3. Blog
        - Blog 의 Tile,내용 ,Description 구현
        - 태그 찾는 기능 구현 
        - Blog 날짜별로 Search 기능 구현 
<img src="/Results/Blog_List.png">  
<img src="/Results/Blog_Detail.png">  
<img src="/Results/Tag.png">  
<img src="/Results/Post_Archieve.png">  

## 4. Add,Change
        - 각각의 앱들에 대한 Add ,Change 기능 추가
        - admin 사용자는 모든 게시글에 대한 수정 ,삭제 가능 
        - 일반 사용자는 자신의 글에대해서만 권한 가짐

<img src="/Results/Post_Update.png">       
<img src="/Results/Change.png">  

## 5. User Account 
        - 계정 생성 및 비밀번호 변경기능 추가 
<img src="/Results/User_Change.png">  


