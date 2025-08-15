# mini-rag

this is a minimal implementation of the RAG model for question answering 

## Requriments

- python 3.8 or later

### Install python using miniconda 

1) Download and install miniconda from [here](https://www.anaconda.com/download/success) 

2) Create a new environment using the following command :
```bash 
$ conda create -n mini-rag-app  python=3.8
```

3) Activate the environment:
```bash
$ conda activate mini-rag-app
```

### (Optional) Setup your command line interface for better readability
```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$"
```
## Installation

### Install required Packages
```bash
$ pip install -r requirements.txt
```
### Setup the environment variables 
```bash
$ cp .env.example .env
```

Set your environment variables in the `.env` file, like `OPEN_API_KEY` value.




