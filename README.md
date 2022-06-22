# 사장님 주문 관리 애플리케이션 
### 기능 명세 <br>
모든 주문을 조회할 수 있으며, 주문이 접수되면 수락/거절을 할 수 있다.<br>
주문한 음식이 조리가 완료되면 픽업 가능함을 알릴 수 있다. (배달 요청)<br>
라이더가 배달을 수락했는지, 배달중인지, 또는 배달을 완료했는지 여부를 확인할 수 있다.<br>

# Deployment Automation


![GitHub Workflow Status (event)](https://github.com/cs-devops-bootcamp/devops-01-P2-TeamD/actions/workflows/API_Test.yml/badge.svg?event=push) ![GitHub Workflow Status (event)](https://github.com/cs-devops-bootcamp/devops-01-P2-TeamD/actions/workflows/ci-to-ecr.yml/badge.svg?event=push) [![Deploy Release to AWS ECS](https://github.com/cs-devops-bootcamp/devops-01-P2-TeamD/actions/workflows/release-to-ecs.yml/badge.svg)](https://github.com/cs-devops-bootcamp/devops-01-P2-TeamD/actions/workflows/release-to-ecs.yml?event=release) ![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/cs-devops-bootcamp/devops-01-P2-TeamD?include_prereleases)

애플리케이션의 서버는 [`Fastify-CLI`](https://www.npmjs.com/package/fastify-cli)로  만들어졌습니다.
  
Server of this project was bootstrapped with [`Fastify-CLI`](https://www.npmjs.com/package/fastify-cli).

-------------------------------

## 실행 방법 Available Scripts


프로젝트 폴더 위치에서,

In the project directory, you can run:

### `npm install`

를 입력하면 서버 구동이 필요한 라이브러리 등을 설치합니다.

Install tools needed to run this server.

### `npm run dev`

를 입력하면 개발모드로 서버를 실행합니다.
[http://localhost:3000](http://localhost:3000)에 접속하면,
서버가 동작중임을 확인할 수 있습니다.

To start the app in dev mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.


### `npm start`

배포모드로 실행합니다.
`0.0.0.0`의 주소로 `5000` 포트에서 실행됩니다.

For production mode
In this mode, the server was run in `0.0.0.0` ip address and port number, `5000`

### `npm run test`

API 테스트를 해볼 수 있습니다

Run the test cases of the server, API test.

## Fastify가 궁금하다면?, Learn More Fastify

[Fastify documentation](https://www.fastify.io/docs/latest/)
여기서 Fastify에 대해 더 자세히 설명합니다.

To learn Fastify, check out the [Fastify documentation](https://www.fastify.io/docs/latest/).
