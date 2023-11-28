# Amazon SQS code examples for the SDK for Python

## Overview

Shows how to use the AWS SDK for Python (Boto3) to work with Amazon Simple Queue Service (Amazon SQS).

*Amazon SQS is a fully managed message queuing service that makes it easy to decouple and scale microservices, distributed systems, and serverless applications.*

## Code examples

### Single actions

Code excerpts that show you how to call individual service functions.

* [Create a queue](queue_wrapper.py#L23) (`CreateQueue`)
* [Delete a batch of messages from a queue](message_wrapper.py#L143) (`DeleteMessageBatch`)
* [Delete a message from a queue](message_wrapper.py#L124) (`DeleteMessage`)
* [Delete a queue](queue_wrapper.py#L92) (`DeleteQueue`)
* [Get the URL of a queue](queue_wrapper.py#L51) (`GetQueueUrl`)
* [List queues](queue_wrapper.py#L70) (`ListQueues`)
* [Receive messages from a queue](message_wrapper.py#L94) (`ReceiveMessage`)
* [Send a batch of messages to a queue](message_wrapper.py#L51) (`SendMessageBatch`)
* [Send a message to a queue](message_wrapper.py#L24) (`SendMessage`)

### Scenarios

Code examples that show you how to accomplish a specific task by calling multiple
functions within the same service.

* [Send and receive batches of messages](message_wrapper.py)

## Run the examples

#### Send and receive batches of messages

This example shows you how to do the following:

* Create an Amazon SQS queue.
* Send batches of messages to the queue.
* Receive batches of messages from the queue.
* Delete batches of messages from the queue.


Start the example by running the following at a command prompt:

```
python message_wrapper.py
```
