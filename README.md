# node-sequelize

## 목차

1. [용어 설명](#1-용어-설명)
2. [설치](#2-설치)
3. [사용법](#3-사용법)

___

## 1. 용어 설명
> sequelize란? ORM 라이브러리 <br>
  ORM(Object Relational Mapping) -> 자바스크립트 객체와 관계형 데이터베이스를 서로 연결해주는 도구
* migration -> 데이터베이스 테이블 필드 정보 or 구조 등이 바뀌는 특수한 상황에 사용
* model -> 데이터베이스 테이블 필드 정보를 작성할 때 사용
* seeder ->  
* association -> 관계 설정에 대한 정의를 함
    
___

## 2. 설치
```
$ npm i sequelize mysql2 //모듈 설치
$ npm i -g sequelize-cli //콘솔 명령 모듈
$ sequelize init //sequelize 자동 설치
```
___

## 3. 사용법
* config.json -> config.js로 변경한다.
* config.js에 DB 정보를 입력한다.
* models > index.js > 8번줄을 수정한다. -> config.js
* app.js에 sequelize을 연결해준다. -> 13번줄 참고
* models에 테이블 파일을 만든다.
  *id는 자동으로 생성됨 <br>
  *테이블명은 복수형으로 생성되므로 옵션에 tableName을 명시해줘야함 <br>

