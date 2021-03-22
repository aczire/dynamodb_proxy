# dynamodb_proxy

Skip Lambda, Save Data to DynamoDB Directly Using API Gateway;
Gives much more scalability and performance.

There are two examples in here.
1. Transform input using VTL template and write to DynamoDB
    Best for API integration with data coming from unknown sources, front-end etc.
2. Pass through the input directly to DynamoDB.
    Best for API integrations with data coming from known sources with high control over the input data schema.
