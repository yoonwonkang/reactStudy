## START REACT (MAC)

1. node.js Install
```
$ brew install node
```
** version이 낮을 경우 버전업해준다.

2. install npm
```
$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash

$ nvm install --lts
```

3. yarn install
```
$ brew install yarn
```
** 만약 PATH를 제대로 인식하지 못할 경우 
```
$ echo 'export PATH="$(yarn global bin):$PATH"' >> ~/.bash_profile
```

4. create-react-app 
Webpack, Babel tool 설치
Webpack -> 여러가지 파일을 한개로 결합
Babel -> 새로운 자바스크립트 문법 사용 용도
```
$ create-react-app hello-react
```

5. react start
4번의 명령어를 실행시킨 dir로 가서
```
$ cd hello-react  //자신이 설치한 폴더
$ yarn start
```
