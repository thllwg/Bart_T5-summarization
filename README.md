# Run the Text summarization Flask app in Docker
---
Thanks to [Renato violin](https://www.linkedin.com/in/renato-violin-6681913b/) for building a [Flask App to enable users to play around with Text summarization using BART and T5](https://github.com/renatoviolin/Bart_T5-summarization).

This repository provides a Dockerfile to fiddle around with text summarization using BART and T5 in Docker.

## How to use this Dockerfile

    docker build -t bart_t5 .
    docker run  --name bart_t5 -p 0.0.0.0:8000:8000 bart_t5

Once the container is started, open the application in your webbrowser under the specified url and port address.

## Bart_T5-summarization
Summarization Task using Bart and T5 models from [HugginFace Transformers](https://github.com/huggingface/transformers)

It is possible to directly compare the best models for text summarization Bart and T5.  

### Bart Summarization
![Bart Summarization](bart.png)

### T5 Summarization
![Bart Summarization](t5.png)
