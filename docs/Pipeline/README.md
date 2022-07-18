## Pipeline

From the root of the project:

- `npm run frontend:install`    - To install frontend dependencies.
- `npm run frontend:build`      - To build the Angular/Frontend.
- `npm run frontend:deploy`     - To deploy the project to S3 using `./udagram-frontend/bin/deploy.sh` deploy script.
- `npm run api:install`     - To install backend dependencies.
- `npm run api:build`       - To transpile the Typescript/Backend.
- `npm run api:deploy`      - To deploy the project to EB using `./udagram-api/bin/deploy.sh` deploy script.

## CircleCi

The order of the run jobs:

- Setting Env Variables.
- Install NodeJS.
- Checkout Code & Cloning the Repo.
- Install AWS CLI v2.
- Install AWS Elastic Beanstalk CLI.
- Configure AWS AccessKeyID.
- Configure AWS Region.
- Frontend:
  - Install dependencies.
  - Build the angular.
  - Deploy the site to AWS S3.
- Backend:
  - Install dependencies.
  - Transpile the typescript/ build the app.
  - Deploy the app to AWS Elastic Beanstalk.
