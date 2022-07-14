IO needs to be done differently. <br>
Ryan Dahl, JSConf 2009
================================
<br><br>

# Node.js 의 특징

- 비동기식 처리 방식 (콜백함수 사용 _ 요청하고 기다리기 처리 방식 방지)
- 빠른 속도와 높은 확장성 (Offloading _ 저수준의 오래 걸리는 일은 Node에게, 고수준의 로직은 메인 스레드에서 해결)
- 저수준 처리가 느림 (C와 WebAssembly 모듈을 바인딩해 사용하는 방법으로 해결)
- npm (Node Package Manager) 으로 인한 방대한 오픈 소스 생태계

<br><br>

## dependencies package 정리
<br>

<br>

## devDependencies package 정리
<br>

### 1. prettier : Formatting

- Config file : .prettierrc

- VSCode extensions : O

<br>

### 2. eslint : Linting

- Additional dependencies :
    - eslint-config-airbnb-base
    - eslint-config-prettier
    - eslint-plugin-import
    - eslint-plugin-node

- Config file : .eslintrc.js

- VSCode extensions : O

<br>

### 3. typescript : Type checking

- Additional dependencies : @type/node

- Config file : jsconfig.json

<br> 

