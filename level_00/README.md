# Level_00

[AWS CDK v2](https://docs.aws.amazon.com/ko_kr/cdk/v2/guide/home.html) 공식 문서를 따라 초기 세팅 및 따라해보기

## 1. AWS CDK v2 설치

- `aws-cdk` 를 global로 설치

```shell
npm install -g aws-cdk
```

- `aws-cdk` 설치 버전 확인

```shell
cdk --version
```

2.39.0 (build e36bfe5) 와 같이 버전이 출력됨.

- 프로젝트 생성할 폴더 `cdk-workshop` 을 하나 만들어줌

```shell
mkdir cdk-workshop && cd cdk-workshop
```

- cdk init 으로 TypeScript CDK 프로젝트 초기 세팅

```shell
cdk init sample-app --language typescript
```
