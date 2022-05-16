# Udagram

This is a project where we introduce to the AWS SERVICES and practice how to implement an application using ELASTICK BEANSTALK, S3 BUCKET, AWS RDB. Also we are going to set the pipeline working with CIRCLECI

## Getting Started

1. Clone this repo from Github (https://github.com/Fanfarlo/udagram.git)
2. Go inside each folder udagram-api ``cd udagram-api`` and udagram-frontend ``cd udagram-frontend``. Then install all dependencies in each location ``npm install``
3. Set the emvironment variables inside a file call ``.env`` in the udagram-api folder:
    * AWS_ACCESS_KEY_ID
    * AWS_DEFAULT_REGION
    * AWS_SECRET_ACCESS_KEY
    * JWT_SECRET
    * POSTGRES_DB
    * POSTGRES_HOST
    * POSTGRES_PASSWORD
    * POSTGRES_PORT
    * POSTGRES_USERNAME
    * PORT
    * URL
4. Go and Run inside udagram-frontend folder ``npm run dev``
5. Go and Run inside udagram-api folder ``npm run start``
6. In your browser go to (http://localhost:4200)

### FRONTEND LINK
``http://frontendmiguelo.s3-website-us-east-1.amazonaws.com``

### Dependencies

```
- Node v16.14.2 (LTS) or more recent

- npm 8.5.0 (LTS) or more recent

- AWS CLI 2.5.7 and Python 3.9.11

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

## Testing

For testing you can follow this steps

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`


### Unit Tests and End to End Test:

- Unit tests are using the Jasmine Framework.
- The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
