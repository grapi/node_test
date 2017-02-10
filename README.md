# Node And MongoDB

## node_test

### Node Install (MAC)

```
$ brew update
$ brew upgrade

$ brew search node ### 노드 관련 패키지 정보를 알아본다
$ brew info node ### 노드 설치 정보를 알아본다
$ brew install node ### 노드를 설치한다
$ node --version ### 노드가 잘 설치됐는지 확인한다

$ npm ls --global --depth=0 ## 노드 패키지 관리자도 설치되었는지 확인
```

### NPM 시작하기
```
$ npm init
```
package.json 이 생성되며 노드의 어플리케이션/ 모듈의 경로에 위치해 있습니다.
모듈을 설치 하면 패키지의 속성이 정의 되어 있습니다.


### NPM 을 사용하여 모듈 설치 하기

```
$ npm install <모듈이름>
```

- 글로벌 VS 로컬 모듈 설치

```
$ npm install express ## express 설치하기 로컬 모듈 설치

$ sudo npm install express -g ## express 글로벌 설치
$ cd [local path]/project
$ npm link express
```



### 모듈 제거,업데이트,검색
```
$ npm uninstall express
$ npm update express
$ npm search express
```


### 노드 서버 띄우기
현재 가지고 있는 소스를 기준으로 node server 시작하기
```
$ node server.js
```



### 참고 사이트
> ref : https://medium.com/@lambdavc/%EB%A7%A5-%EC%9A%B4%EC%98%81-%EC%B2%B4%EC%A0%9C-%EC%8B%9C%EC%97%90%EB%9D%BC%EC%97%90-%EB%85%B8%EB%93%9C-%EC%84%A4%EC%B9%98%ED%95%98%EA%B8%B0-3316f7dcd364#.kc74gp3mg
