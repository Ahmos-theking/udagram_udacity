# Dployment a Full-Stack Application

## Tools and Services:

For this project I used Circle CI For CI/CD automating pipeline to deploy this project to AWS cloud

- in the AWS Cloud I used these services:

-AWS RDS : for hosting postgres database
-AWS Elastic Beanstalk : for hosting the web server
-AWS S3 Bucket : for hosting the frontEnd

# Project URLs

FrontEnd url : http://ahmos-udagram.s3-website-us-east-1.amazonaws.com/home
BackEnd url :http://udagram-api-dev.eba-m2nevqpp.us-east-1.elasticbeanstalk.com
Database url : udagram.cdomypvb04vt.us-east-1.rds.amazonaws.com

### Environment variables

POSTGRES_HOST: database host url
POSTGRES_DB: database name
POSTGRES_USERNAME: database user name
POSTGRES_PASSWORD: database password
DB_PORT: database port
PORT: server port
AWS_DEFAULT_REGION: aws region
AWS_BUCKET: s3 bucket name
URL: BackEnd url
JWT_SECRET: secret-key
AWS_SECRET_ACCESS_KEY: aws secret key
AWS_ACCESS_KEY_ID: aws access ID

### local installation

first of all create you local database and connect it

#### back-end install

- npm install
- npm run build
- npm run start

#### front-end install

-npm install
-npm run build
-npm run start
#   u d a g r a m _ u d a c i t y  
 