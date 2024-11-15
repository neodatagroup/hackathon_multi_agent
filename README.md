# Multi Agent Systems Hackathon powered by Neodata



PDF Presentation: https://www.canva.com/design/DAGWR1YbdBE/7mMDgkeJow8AsvU-GYoMbA/edit?utm_content=DAGWR1YbdBE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton


## Setup

### Python version

To get the most out of this tutorial, please ensure you're using Python 3.11 or later. 
This version is required for optimal compatibility with LangGraph. If you're on an older version, 
upgrading will ensure everything runs smoothly.
```
python3 --version
```

### Clone repo
```
git clone https://github.com/neodatagroup/hackathon_multi_agent.git

```

### Create an environment and install dependencies
#### Mac/Linux/WSL
```
$ python3 -m venv neohackathon-env
$ source neohackathon-env/bin/activate
$ pip install -r requirements.txt
```
#### Windows Powershell
```
PS> python3 -m venv neohackathon-env
PS> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
PS> neohackathon-env\scripts\activate
PS> pip install -r requirements.txt
```

### Running notebooks
If you don't have Jupyter set up, follow installation instructions [here](https://jupyter.org/install).
```
$ jupyter notebook
```

### Setting up env variables
Briefly going over how to set up environment variables. You can also 
use a `.env` file with `python-dotenv` library.
#### Mac/Linux/WSL
```
$ export API_ENV_VAR="your-api-key-here"
```
#### Windows Powershell
```
PS> $env:API_ENV_VAR = "your-api-key-here"
```

### Set OpenAI API key
* If you don't have an OpenAI API key, you can sign up [here](https://openai.com/index/openai-api/).
*  Set `OPENAI_API_KEY` in your environment 


### Set up Tavily API for web search

* Tavily Search API is a search engine optimized for LLMs and RAG, aimed at efficient, 
quick, and persistent search results. 
* You can sign up for an API key [here](https://tavily.com/). 
It's easy to sign up and offers a very generous free tier. 
* Set `TAVILY_API_KEY` in your environment.
