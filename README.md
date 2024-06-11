# LLM Introduction Notebooks

## Overview

This repository, `gpsandhu23/llm_intro_notebooks`, contains a series of Jupyter notebooks designed to introduce and explore various aspects of Language Learning Models (LLMs). The notebooks cover a range of topics including:

- Introduction to LLMs
- Summarization techniques
- Building chat applications
- Retrieval Augmented Generation (RAG)
- Schema extraction
- Tools for LLMs
- Building AI agents

Each notebook is self-contained and provides a hands-on approach to learning about LLMs.

## Prerequisite
* Python ( make sure you have python installed on your system). You can install python in any of the following ways
  * `brew install python`
  * Directly download and install from - https://www.python.org/downloads/

## Setup Instructions

To get started with these notebooks, you will need to set up your environment:

1. Clone this repository to your local machine.
2. Install the required dependencies listed in `requirements.txt` by running `pip install -r requirements.txt`.
3. Ensure you have Jupyter installed to run the notebooks. If not, it can be installed via pip with `pip install jupyter`.

## Environment Variables

Some notebooks require API keys to access external services like OpenAI, Langchain, and Google API. To set these up:

1. Copy the `.env_example` file to a new file named `.env`.
2. Fill in the `.env` file with your API keys.

## Troubleshooting
While installing required dependencies using `requirement.txt` if you get following error
```
 Building wheel for chroma-hnswlib (pyproject.toml) ... error
  error: subprocess-exited-with-error
  
  × Building wheel for chroma-hnswlib (pyproject.toml) did not run successfully.
  │ exit code: 1
  ╰─> [17 lines of output]
```
Try re-running install again with after setting env variable HNSWLIB_NO_NATIVE as 1
* on Mac - `export HNSWLIB_NO_NATIVE=1 `
* On Win - `set HNSWLIB_NO_NATIVE=1`

## Contributing

Contributions to this repository are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.
