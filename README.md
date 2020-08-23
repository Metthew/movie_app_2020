# Movie App 2020

React JS 2020 Update!


1. Install nvm-windows.
Link : https://github.com/coreybutler/nvm-windows/releases
Download : nvm-setup.zip

nvm-windows 사용법
참고 : https://github.com/coreybutler/nvm-windows#usage

  a. nvm instaill v12.18.2 (install할 node.js 버전)

  b. nvm ls를 입력하여 현재 설치된 nodejs 버전을 확인한다.

  c. nvm use 12.18.2를 입력하여 nodejs를 활성화 시킨다. 
  npm은 nodejs를 설치하면 함께 설치되므로 추가적으로 설치 할 필요가 없다.

2. npm install npx -g

npx는 npm 레지스트리의 패키지 사용 경험을 파악하기 위한 도구이다.

npm : 레지스트리에서 호스팅되는 종속성(dependency)을 매우 쉽게 설치하고 관리할 수 있으며
npx : 레지스트리에서 호스팅되는 CLI도구 및 기타 실행 파일을 쉽게 사용할 수 있다고 한다.

npx가 npm과 가장 다른 점은

- npx는 최신버전에 해당하는 패키지를 설치하여 실행하고, 실행된 이후에 해당 패키지를 제거한다.

3. 프로젝트 만들기

npx create-react-app moive_notice (프로젝트를 만들고 싶은 위치로 가서 create-react-app 오른쪽에 프로젝트 이름입력)

4. cmd에서 code moive_notice 입력하면 해당 프로젝트로 VSCode가 열린다.

5. github연동하기
a. VSCode 콘솔창에서 git init 입력

b. github에서 저장소 만들기(헷갈리지 않기위해서 package.json의 프로젝트 이름과 똑같은 이름으로 저장소를 만듦)


