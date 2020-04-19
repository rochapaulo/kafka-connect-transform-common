# kafka-connect-transform-common
---
[![Build Status](https://travis-ci.org/rochapaulo/kafka-connect-transform-commons.svg?branch=master)](https://travis-ci.org/rochapaulo/kafka-connect-transform-commons)

### ExtractTopic
```yaml
  CONNECTOR_TRANSFORMS: "extract-topic-name"
  CONNECTOR_TRANSFORMS_EXTRACT-TOPIC-NAME_TYPE: aalmeida.paulorocha.kafka.connect.transform.common.field2header.ExtractTopicExtractTopic
  CONNECTOR_TRANSFORMS_EXTRACT-TOPIC-NAME_VALUE: "header.topic"
  CONNECTOR_TRANSFORMS_EXTRACT-TOPIC-NAME_DELIMITER: \\.
``` 

```json
{
    "header": {
        "topic": "target-topic-name"
    },
    "body": {
        "name": "Paulo",
        "surname": "Almeida",
        "dateOfBirth": "24-10-1990"
    }
}
```
