node.js, express, ejs, sqlite3

작업 이전에 npm install 명령어로 package.json에 있는 모든 라이브러리 다운

db primary key 초기화: UPDATE SQLITE_SEQUENCE SET seq = 0 WHERE name = '{TABLE_NAME}';

git pull 에러 해결 방법:
    - 현재 디렉토리의 파일을 임시로 백업하고 깨끗한 상태로 돌린다.
    
    #git stash
    #git pull origin master
    #git stash pop
