
# 2020-2-ESCD-YeongSeoYeonGeun
2020년도 기업사회맞춤형프로젝트2_01 영서연근


## Project
* 2020년 2학기 기업사회맞춤형프로젝트 영서연근팀
* 유학생을 위한 교내 카페 사이렌 오더 시스템 Uorders


# Backend



## 참여 인원
|이름|역할|
|------|---|
|박종근|유학생용 미니프로그램, 점주용 IOS 애플리케이션|
|이영서|점주용 IOS 애플리케이션|


## Dependencies

```
dependencies {
	compile group: 'com.googlecode.json-simple', name: 'json-simple', version: '1.1.1'
	compile 'com.fasterxml.jackson.datatype:jackson-datatype-jsr310'
	implementation 'org.springframework.boot:spring-boot-starter-data-jpa'
	implementation 'org.springframework.boot:spring-boot-starter-thymeleaf'
	implementation 'org.springframework.boot:spring-boot-starter-web'
	implementation 'com.google.firebase:firebase-admin:6.8.1'
	implementation group: 'com.squareup.okhttp3', name: 'okhttp', version: '4.2.2'
	compile 'com.google.cloud:google-cloud-translate:1.95.4'
	compileOnly 'org.projectlombok:lombok'
	runtimeOnly 'mysql:mysql-connector-java'
	annotationProcessor 'org.projectlombok:lombok'
	testImplementation('org.springframework.boot:spring-boot-starter-test') {
		exclude group: 'org.junit.vintage', module: 'junit-vintage-engine'
	}
}
```

## 서버 아키텍쳐
![그림1](https://user-images.githubusercontent.com/53558710/102711258-875a5200-42fb-11eb-8ed4-00298f4b3691.png)


## 사용된 도구
* Springboot
* MySQL
* Firebase Cloud Messaging
* Google Cloud Translate
* Okhttp3
* AWS EC2
* AWS RDS
* AWS S3



---


# Frontend


## 참여 인원
|이름|역할|
|------|---|
|양시연|유학생용 미니프로그램(70%), 점주용 IOS 애플리케이션(30%)|
|이선영|점주용 IOS 애플리케이션(70%), 유학생용 미니프로그램(30%)|


## Feature

#### 유학생 용 미니프로그램
 - 다국어 지원(한글, 중국어, 영어)
 - 교내 모든 카페에서 주문 가능
- 카페에서 주문 접수 시 번호 발급
- 위챗 페이로 결제 가능

#### 점주용 iOS 어플리케이션
- 카페 메뉴 관리
- 주문 들어오면 소요 시간 입력
- 주문 관리
- 수익 내역 확인


## 시연 영상

#### 유학생용
https://user-images.githubusercontent.com/37260938/102711662-c1792300-42fe-11eb-9de6-a8cb626fed6c.mp4

#### 점주용
https://user-images.githubusercontent.com/37260938/102711765-7f041600-42ff-11eb-9c33-e9879db57970.mp4

## 사용된 도구
* WechatDeveloper Tool
* Xcode
* Github
* Zeplin
* Postman

## 사용된 라이브러리
- Alamofire
- SwiftyJSON
- Wechat Library
