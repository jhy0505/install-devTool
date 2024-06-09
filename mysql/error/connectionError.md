# [MySQL] Public Key Retrieval is not allowed 에러 해결

<br/>

## 1. 에러 이미지
![image1](/mysql/images/240609-3.png)

<br/>

### 해석: 공개 키 검색은 허용되지 않습니다.

<br/>

* 주로 클라이언트가 MySQL 서버에 연결할 때 발생.
* MySQL 서버의 인증 방식과 관련이 있으며, 보안 설정으로 인해 발생.

<br/>

## 2. 원인: MySQL 8.0 버전 및 이후 버전의 보안 강화
* MySQL 8.0에서는 보안 강화를 위해 클라이언트와 서버 간의 공개 키 교환을 제한하는 설정이 기본적으로 활성화되어 있음.

<br/>

## 3. 해결 방법

<br/>

### 해당 서버에서 우클릭 후, Edit Connection 클릭
![image2](/mysql/images/240609-4.png)

<br/>

### Connection 설정 팝업에서 Driver properties 탭 클릭
![image3](/mysql/images/240609-5.png)

<br/>

### Driver properties 이름이 allowPublicKeyRetrieval의 값을 TRUE로 변경
![image4](/mysql/images/240609-6.png)

<br/>

### 위 설정 적용하면 MySQL 서버에 정상적으로 연결됨.