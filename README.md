# Project Title

Artillery performance testing framework, suitable for NodeJS applications

## Getting Started

Run command npm install
Run ./node_modules/.bin/artillery run .\tests\artillery.yml

### Prerequisites

What things you need to install the software and how to install them

```
NodeJS installed
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Clone this repository
Run npm install
Run artillery run artillery.yml
```

You will receive a report such as:
Complete report @ 2019-01-02T17:32:36.653Z
  Scenarios launched:  300
  Scenarios completed: 300
  Requests completed:  600
  RPS sent: 18.86
  Request latency:
    min: 52.1
    max: 11005.7
    median: 408.2
    p95: 1727.4
    p99: 3144
  Scenario counts:
    0: 300 (100%)
  Codes:
    200: 300
    302: 300

```

## Acknowledgments

* Artillery.io built this demo
* https://artillery.io/docs/getting-started/
