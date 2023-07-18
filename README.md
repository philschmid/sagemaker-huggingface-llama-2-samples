# Getting Started with LLaMa 2 and Hugging Face

This repository contains instructions/examples/tutorials for getting started with LLaMA 2 and Hugging Face libraries like [transformers](https://huggingface.co/docs/transformers/index), [datasets](https://huggingface.co/docs/datasets/index).

### Training

* [Fine-tune LLaMA 2 on Amazon SageMaker](./training/sagemaker-notebook.ipynb) 

## Requirements

Before we can start make sure you have met the following requirements

* AWS Account with quota
* [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html) installed
* AWS IAM user [configured in CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html) with permission to create and manage ec2 instances

### Commands 

```bash
watch -n0.1 nvidia-smi
```