# ![LOGO](logo.png) Qakka **flow**ground Connector

## Description

A generated **flow**ground connector for the Qakka API (version v1).

Generated from: https://api.apis.guru/v2/specs/apache.org/qakka/v1/swagger.json<br/>
Generated at: 2019-06-06T16:11:40+03:00

## API Description

API for Qakka Queue System

## Authorization

This API does not require authorization.

## Actions

### Get list of all Queues.

*Tags:* `queues`

### Create new queue.

*Tags:* `queues`

### Delete Queue.

*Tags:* `queues`

#### Input Parameters
* `queueName` - _required_
* `confirm` - _optional_

### Get Queue config.

*Tags:* `queues`

#### Input Parameters
* `queueName` - _required_ - Name of Queue

### Update Queue configuration.

*Tags:* `queues`

#### Input Parameters
* `queueName` - _required_

### Get data associated with a Queue Message.

*Tags:* `queues`

#### Input Parameters
* `queueName` - _required_ - Name of Queue
* `queueMessageId` - _required_ - ID of Queue Message for which data is to be returned

### Get next Queue Messages from a Queue

*Tags:* `queues`

#### Input Parameters
* `queueName` - _required_ - Name of Queue
* `count` - _optional_ - Number of messages to get

### Send Queue Message with a binary data (blob) payload.

*Tags:* `queues`

#### Input Parameters
* `queueName` - _required_ - Name of Queue
* `regions` - _optional_ - Regions to which message is to be sent
* `delay` - _optional_
* `expiration` - _optional_
* `contentType` - _required_ - Content type of the data to be sent with Queue Message

### Acknowledge that Queue Message has been processed.

*Tags:* `queues`

#### Input Parameters
* `queueName` - _required_ - Name of Queue
* `queueMessageId` - _required_ - ID of Queue Message to be acknowledged

### Status of webapp.

*Tags:* `status`

## License

**flow**ground :- Telekom iPaaS / apache-org-qakka-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
