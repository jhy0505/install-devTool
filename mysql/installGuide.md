# MySQL 설치 방법

<br/>

## 1. MySQL 홈페이지 접속
[MySQL 다운로드 링크 (https://dev.mysql.com/downloads/installer/)](https://dev.mysql.com/downloads/installer/)

<br/>

## 2. MySQL Installer 다운로드
### 2024년 5월 13일 기준 최신 버전 : **8.0.37**

<br/>

### 설치 파일에 모든 내용이 들어있는 아래쪽 파일 다운로드
![image1](/mysql/images/240513-1.png)

<br/>

### 'No thanks, just start my download.'를 클릭해서 로그인 하지 않고 바로 다운로드
![image2](/mysql/images/240513-2.png)

<br/>

## 3. 다운로드 완료 후 MySQL Installer 실행
### Custom 클릭 후, 우측 하단 'Next >' 버튼 클릭
![image7](/mysql/images/240515-5.png)

<details>
  <summary><h3>설치 타입 자세히 보기</h3></summary>

  * **Server only** : Installs only the MySQL Server product. ( MySQL 서버만 설치 )
  ![image3](/mysql/images/240515-1.png)

  <br/>

  * **Client only** : Installs only the MySQL Client products, without a server. ( MySQL 애플리케이션 관리에 필요한 도구만 설치 )
  ![image4](/mysql/images/240515-2.png)

  <br/>

  * **Full** : Installs all included MySQL products and features. ( 모든 제품 설치 )
  ![image5](/mysql/images/240515-3.png)

  <br/>

  * **Custom** : Manually select the products that should be installed on the system. ( 사용자에게 필요한 제품만 설치할 수 있도록 선택 가능 )
  ![image6](/mysql/images/240515-4.png)
</details>

<br/>

### 다음 이미지와 같이 커스텀 후, 우측 하단 'Next >' 버튼 클릭
![image8](/mysql/images/240515-6.png)

<details>
  <summary><h3>사용 가능 제품 자세히 보기 및 추가 옵션 설명</h3></summary>

  * MySQL Servers
    * MySQL Server : 데이터 베이스 서버 자체를 의미하며, 가장 핵심 시스템

  <br/>

  * Applications
    * MySQL Workbench : MySQL 데이터베이스를 시각적으로 관리하기 위한 GUI 도구
    * MySQL Shell : CMD에서 MySQL과 상호 작용하기 위한 공식 인터페이스로 데이터베이스 관리 및 쿼리 실행을 지원
    * MySQL Router : 클라이언트 앱과 MySQL 서버 간의 연결 관리를 담당하는 중간 계층 라우팅 솔루션으로 로드 밸런싱, 장애 조치 및 보안을 포함한 다양한 기능 제공 

  <br/>

  * Documentation
    * MySQL Documentation : MySQL 공식 문서 다운로드
    * Samples and Examples : MySQL 샘플 코드와 예제 코드 다운로드

  <br/>

  * Enable the Select Features Page to customize product features   
    : 설치하는 제품의 더 자세한 설치 프로그램 선택 여부
</details>

<br/>

### 설치할 목록 확인 후, 우측 하단 'Execute' 버튼 클릭
![image9](/mysql/images/240515-7.png)

<br/>

### 우측 하단 'Next >' 버튼 클릭
![image10](/mysql/images/240515-8.png)

<br/>

### 우측 하단 'Next >' 버튼 클릭
![image11](/mysql/images/240515-9.png)

<br/>

### 서버 타입 Development Computer 확인 후, 우측 하단 'Next >' 버튼 클릭
![image12](/mysql/images/240515-10.png)

<br/>

### Authentication Method 권장 옵션 선택 후, 우측 하단 'Next >' 버튼 클릭
![image13](/mysql/images/240515-11.png)

<br/>

### MySQL Root 계정 비밀번호 설정 후, 우측 하단 'Next >' 버튼 클릭
![image14](/mysql/images/240515-12.png)

<br/>

### Windows Service 기본 설정 선택 후, 우측 하단 'Next >' 버튼 클릭
![image15](/mysql/images/240515-13.png)

<br/>

### 우측 하단 'Next >' 버튼 클릭
![image16](/mysql/images/240515-14.png)

<br/>

### 우측 하단 'Execute' 버튼 클릭으로 현재까지 선택한 설정으로 변경
![image17](/mysql/images/240515-15.png)

<br/>

### 우측 하단 'Finish' 버튼 클릭
![image18](/mysql/images/240515-16.png)

<br/>

### 우측 하단 'Next >' 버튼 클릭
![image19](/mysql/images/240515-17.png)

<br/>

### 우측 하단 'Finish' 버튼 클릭으로 MySQL 설치 완료!
![image20](/mysql/images/240515-18.png)