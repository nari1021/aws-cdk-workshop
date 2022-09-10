# Welcome to your CDK TypeScript project

This is a blank project for CDK development with TypeScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

- `npm run build` compile typescript to js
- `npm run watch` watch for changes and compile
- `npm run test` perform the jest unit tests
- `cdk deploy` deploy this stack to your default AWS account/region
- `cdk diff` compare deployed stack with current state
- `cdk synth` emits the synthesized CloudFormation template

## 폴더 구조

- bin/cdk-workshop.ts // CDK 응용 프로그램의 진입점. `lib/cdk-workshop-stack.ts` 정의된 스택을 로드함
- lib/cdk-workshop-stack.ts // CDK 애플리케이션의 메인 스택이 정의되는 곳.
