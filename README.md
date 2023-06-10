# Access

Obtain access to `OPENAI_API_KEY` and `GOOGLE_APPLICATION_CREDENTIALS` by visiting the following links:
- [OpenAI](https://platform.openai.com/docs/quickstart/build-your-application)
- [Google](https://cloud.google.com/vertex-ai/docs/start/cloud-environment)

# Installation

1. Environment management options
   
    a)  Poetry: ```poetry shell```
    
    b) Conda: create and activate a conda env for this project:
```bash
conda create -n prompt-engineering python=3.10
conda activate prompt-engineering
```

2. Install package
```
poetry install
```
3. Check installation worked by running 
```
pytest .
```

4. Create private environment file (this will not be committed!)
```
cp .env-template .env
```
Add any necessary API keys there following the given format.



- `notebooks/start_here.ipynb`: A notebook that shows how to import and call any shared utilities, and demonstrates a baseline to improve on for the final goal.

# Repo Info
## Poetry
We use [poetry](https://python-poetry.org/) as our dependency manager.
The link above has great documentation but there is a TL;DR.

- Install the package: `poetry install`
- Add a dependency: `poetry add <python-lib>`
- Where are dependencies specified? `pyproject.toml` include the high level requirements. The latests exact versions installed are in `poetry.lock`.

