## Serverless with AWS Lambda, S3 and NodeJS

A simple NodeJS function that optimizes and converts a ".jpg or .png" image to ".jpeg", using the **serverless** architecture of amazon: 

- [AWS Lambda](https://aws.amazon.com/pt/lambda/);
- [S3](https://aws.amazon.com/pt/s3/?sc_channel=PS&sc_campaign=acquisition_BR&sc_publisher=google&sc_medium=english_s3_b&sc_content=s3_e&sc_detail=aws%20s3&sc_category=s3&sc_segment=89108864428&sc_matchtype=e&sc_country=BR&s_kwcid=AL!4422!3!89108864428!e!!g!!aws%20s3&ef_id=EAIaIQobChMI9ZbQhrv26gIVAg2RCh0_JQizEAAYASAAEgJwpPD_BwE:G:s&s_kwcid=AL!4422!3!89108864428!e!!g!!aws%20s3);
- [IaC CloudFormation](https://aws.amazon.com/pt/cloudformation/);

# Working

- to configure IAM aws

```bash
$ serverless config credentials --provider aws --key=<AWS_KEY> --secret <SECRET_KEY>

```

- to create your working environment

```bash
$ npm run deploy
```


Copyright (c) [2020] [Yuri Mussi]