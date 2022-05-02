# node-sequelize

<p>
    <h3>1. 용어 설명</h3>
    1-1. <strong>sequelize란?</strong> ORM 라이브러리<br>
    *ORM(Object Relational Mapping) -> 자바스크립트 객체와 관계형 데이터베이스를 서로 연결해주는 도구<br>

    1-2. <strong>migration</strong> -> 데이터베이스 테이블 필드 정보 or 구조 등이 바뀌는 특수한 상황에 사용<br>

    1-3. <strong>model</strong> -> 데이터베이스 테이블 필드 정보를 작성할 때 사용<br>

    1-4. <strong>seeder</strong> ->  <br>

    1-5. association -> 관계 설정에 대한 정의를 함<br>
</p>

<p>
    <h3>2. 설치</h3>
    $ npm i sequelize mysql2 //모듈 설치
    $ npm i -g sequelize-cli //콘솔 명령 모듈
    $ sequelize init //sequelize 자동 설치
</p>

<p>
    <h3>3. 사용법</h3>
    3-1. dotenv 사용을 위해 config.json -> config.js로 변경한다.<br>
    3-2. config.js에 DB 정보를 입력한다.<br>
    3-3. models > index.js > 8번줄을 수정한다. -> config.js<br>
    3-4. app.js에 sequelize을 연결해준다. -> 13번줄<br>
    3-5. models에 테이블 파일을 만든다.<br>
      *id는 자동으로 생성됨<br>
      *테이블명은 복수형으로 생성되므로 옵션에 tableName을 명시해줘야함<br>
</p>