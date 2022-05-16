# Pipeline 

We are going to work with CircleCI and Github

## Steps 

The orbs for AWS CLI, NODE and EB CLI are in the ``config.yml`` file inside ``.circleci`` folder

 1. Preparing Environment 
    - Setup Node, npm, AWS cli, Eb cli
 2. Installing 
    - run ``npm install`` for frontend and backend
 3. Building
    - Run ``npm run build`` for frontend and banckend
 4. Deploying
    - run ``npm run deplou`` for frontend and backend