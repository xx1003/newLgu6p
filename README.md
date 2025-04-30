# newLgu6p : mini streamlit project
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

## streamlit 대시보드 개발
- sqlite3와 연결

## 대시보드 디자인
- 테스트 완료 후
    1. 데이터베이스를 데이터프레임 형태로 출력
    2. 그래프로 시각화
![Image](https://github.com/user-attachments/assets/4e0eddb3-9612-47fd-b534-9fc72954f663)
![Image](https://github.com/user-attachments/assets/c88035cf-c871-4c1e-8529-4f9b3b00a119)
![Image](https://github.com/user-attachments/assets/b4b8073d-5800-48e9-8e55-8e5fd9462627)
![Image](https://github.com/user-attachments/assets/dee7aee9-2811-413d-9d02-bb6e2d2afc1b)

### 배포 deploy, streamlit 웹사이트
- streamlit 으로 배포
    - 배포 링크 : <https://newlgu6p-2fytzw9wwthe2yvu2e4slf.streamlit.app/>
- README.md 페이지 구성
    + README.md 페이지 구성
        * 마크다운 문법 
            1. 링크 첨부 : <>
            2. 이미지 첨부 : using github issues 
            3. 제목 : #, ##, ###
            4. 번호 X 문단 : -, +, *