This is a simple Node.js application demonstrating the use of RabbitMQ on Cloud Foundry.

## Deploying to Cloud Foundry ##

After installing in the 'cf' [command-line interface](http://docs.cloudfoundry.com/docs/using/managing-apps/cf/) for Cloud Foundry, targeting a Cloud Foundry instance, and logging in, the application can be pushed using these commands:

    $ cf push
    ...
    Push successful! App 'rabbitmq-node' available at http://rabbitmq-node-12345.cfapps.io
