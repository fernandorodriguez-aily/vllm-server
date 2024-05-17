# vllm-server

This repository is focused on the dependencies and aspects of a VLLM server

## Installation

```
poetry install
```

## Run

https://docs.vllm.ai/en/latest/serving/openai_compatible_server.html

### Using Python

```
poetry shell

python -m vllm.entrypoints.openai.api_server --model NousResearch/Meta-Llama-3-8B-Instruct --dtype auto
```

## Development

### Re-create repository

```
poetry init --python ">=3.10.6,<3.11"
```

```
poetry add vllm
```
