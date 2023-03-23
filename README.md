## 23-react1
## 202130403 김수민

## 03.23 4주차 강의 내용
새로운 레파지토리 생성 후 깃 연동 시키기

리드미 파일 이동시키기

방법
1. npx create-react-app [project name] 입력
2. 기존 리드미 파일 복사하기 
3. 생성한 새 프로젝트에 복사한 리드미 파일 붙히고 저장하기
4. 터미널에 git init 라는 명령어 입력하기
5. 터미널에 git commit -m "first commit" 라는 명령어 입력하기
6. 터미널에 git branch -M main 라는 명령어 입력하기
7. 터미널에 git remote add origin 깃주소 입력하기
8. 터미널에 git push -u origin main 이라는 명령어 입력하기 
9. 크롬에서 깃허브 주소로 접속 후 23-react1에 잘 업데이트 되었는지 확인
10. 기존 레파지토리 (23-React1) 삭제하기

## 03.16 3주차 강의 내용

리액트란?
사용자 인터페이스를 만들기 위한 자바스크립트 라이브러리

리액트의 장점
- 동기식과 비동기식
- DOM과 가상 DOM
- 컴포넌트 기반 구조
- 재사용성

리액트의 단점
- 방대한 학습량
- 높은 상태 관리 복잡도

리엑트 파일 생성
1. 원하는 디렉토리 위치로 이동
2. npx create-react-app [project name] 입력
3. 설치 과정이 다 끝나면 해당 app 디렉토리로 이동
4. npm start 입력

종료 시
1. 터미널에 관리자 권한으로 접속
2. netstat -ano 입력
3. ctrl + f 누르고 3000 검색
4. 해당 포트 번호의 pid 를 확인
5. taskkill /f /pid [포트 번호의 pid] 입력

