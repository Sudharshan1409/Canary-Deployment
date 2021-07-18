### lambda-blue-green-deployment

Lambda blue green deployment using AWS `CodeDeploy` and `Lambda Versioning`. For Deployment, here we use `Serverless Framework`. With help of this flow, we can deploy our functions with safety and if any errors occurs it automatically rollback to previous state, while working or deploying in production.

##### Usage:
To see in actions, make sure you have <b>install</b> serverless framework and configure aws cli, if already done just clone the repo at your end and run the followwing command,

```
sls deploy
```

To understand how it works, you could [checkout here]() for the info. 