## Deploy a NextJS app to AWS Fargate with AWS Amplify

 1. Install and configure Amplify CLI and initialize a Amplify project
 2. Configure the project to enable container deployments
 3. Create a Hosted Zone using Route53 Dashboard, configure DNS/register domain name
 4. Add Fargate hosting (A dockerfile is created and we can configure it as required for the NextJS app)
 5. Deploy by 
    ```amplify publish```
6. The Fargate can be configured to use Elastic Load Balancing.