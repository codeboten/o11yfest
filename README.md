# o11yfest
Repository for OpenTelemetry Collector workshop at o11yfest 2022

## Requirements

* Docker compose
* Go 1.16+

## Setup

The first step is setting up the environment that contains the backends,
an instance of the OpenTelemetry Collector and a demo application that is 
generating telemetry. The environment is all contained within a Docker
Compose environment:

```bash
git clone https://github.com/codeboten/o11yfest && cd o11yfest
docker compose up -d
```
