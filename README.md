# Interceptor
'Carrier' 가 사용자의 요청을 받아 작업을 처리하는 인스턴스

## 기술
* Java 8
* Spring Boot (2.1.6 RELEASE)
* MySQL
* JPA
* Gradle
* Azure

## 개요
- 사용자의 요청을 전달 받음 (Start-Date, End-Date) 
- '.csv' 파일 생성
- 파일에 요청받은 기간 만큼 데이터 쓰기 작업
- azure blob storage 에 파일 올리기 (파일 저장해 놓고, 사용자가 원할 때 다운로드 가능하게 함)
- 사용자가 파일 다운로드 