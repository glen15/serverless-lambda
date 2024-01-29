# 람다 배포 자동화

## 서버리스 프레임워크 설치

- `npm install serverless -g`

## 람다 함수 배포

1. 디펜던시 설치

   - `npm install`

2. serverless.yml의 service에 함수명 지정

   - IAM USER-000-lambda로 생성

3. serverless.env_example.yml 설정

   - 파일명 변경 : serverless.env.yml
   - DB_HOST 를 RDS 엔드포인트로 변경
   - OPENAI API KEY 지정

4. 람다 함수 배포

   - `sls deploy`
