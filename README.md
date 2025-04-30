# newLgu6p : 
-------------------------------------
## mysql to sqlite
- sqlite3 생성 후, classicmodels 쿼리 추가 하는 방법
- 참고 링크 : <https://techouse.github.io/mysql-to-sqlite3/>
    - mysql to sqlite 라이브러리 설치
        - 코드
        ```bash
        pip install mysql-to-sqlite3
        ```
    - mysql에서 데이터베이스 sqlite로 가져오기
        - 코드
        ```bash
        mysql2sqlite -f classicmodels sqlite -d classicmodels -u root -p
        ```
    - database에서 sqlite 연결하기

### streamlit 대시보드 개발
- sqlite3와 연결

### 대시보드 디자인
- 테스트 완료 후
    1. 데이터베이스를 데이터프레임 형태로 출력
    2. 그래프로 시각화

### 배포 deploy, streamlit 웹사이트

- README.md 페이지 구성
    + README.md 페이지 구성
        * 마크다운 문법 