Node Practices

1. Node Project(application, library) 만들기
    1) 프로젝트 생성: mkdir로 디렉토리 만들기
        > mkdir project-ex01
    2) 프로젝트 이동: cd 프로젝트 디렉토리
        > cd project-ex01
    3) 프로젝트 초기화: 프로젝트 manifest 파일(package.json)을 생성
        > npm init -y 

2. 패키지
    - 완전한 어플리케이션(babel, webpack, nodemon, Lint, ...)
    - 프로젝트에서 사용하는 라이브러리 모듈(module)

3. 의존성
    - 개발하는 프로젝트(어플리케이션, 라이브러리)에서 설치하는 패키지
        ① 일반 의존성: 개발하고 있는 프로젝트에서 사용하는 패키치로 꼭 빌드와 배포에 포함되어야 한다.
        ② 개발 의존성: 개발에 필요하거나 도음이 되는 패키지로 빌드와 배포에 포함되지 않는다.

4. 패키지 설치
    1) 전역설치
        > npm i -g -D gullp         [전역, 일반]
            > npx gulp --version    (설치 확인)
    2) 지역설치
        > npm i ejs                 [지역, 일반]
        > npm i -D nodemon          [지역, 개발]
    3) 패키지 삭제
        > npm un 패키지명            [지역]
        > npm un -g 패키지명         [전역]              

5. Modules 
    1) 코어 모듈: node에서 기본적으로 제공하는 모듈(fs, os, process, http, ...)
    2) npm 모듈: npm을 통해서 node_modules에 설치하고 사용하는 모듈
    3) 파일 모듈: 파일 경로로 불러온 모듈안에 함수나 객체를 사용한다

6. Server Programming 맛보기