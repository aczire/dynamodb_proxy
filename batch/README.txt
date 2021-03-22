If one or more of the following is true, DynamoDB rejects the entire batch write operation:

One or more tables specified in the BatchWriteItem request does not exist.

Primary key attributes specified on an item in the request do not match those in the corresponding table’s primary key schema.

You try to perform multiple operations on the same item in the same BatchWriteItem request. For example, you cannot put and delete the same item in the same BatchWriteItem request.

Your request contains at least two items with identical hash and range keys (which essentially is two put operations).

There are more than 25 requests in the batch.

Any individual item in a batch exceeds 400 KB.

The total request size exceeds 16 MB.