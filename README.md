<!--
Copyright (C) Pipin Fitriadi - All Rights Reserved

Unauthorized copying of this file, via any medium is strictly prohibited
Proprietary and confidential
Written by Pipin Fitriadi <pipinfitriadi@gmail.com>, 1 August 2024
-->

# OpenAI

Learning repo for OpenAI API based on [docs](https://platform.openai.com/docs/overview).

## Setup

Process this steps at first time in your VS Code after clone this repo:

1. Type `[command]` + `[shift]` + `[P]` >> `Tasks: Run Task` >> `Python: Create VEnv`
2. Type `[command]` + `[shift]` + `[P]` >> `Python: Select Interpreter` >> `./venv/bin/python`
3. Type `[command]` + `[shift]` + `[P]` >> `Tasks: Run Task` >> `Python: Initial setup`
4. Open [`notebook.ipynb`](notebook.ipynb) >> `Select Kernel` >> `Python Environments...` >> `venv/bin/python` >> Install _ipykernel_ package when run notebook script at first time
5. Create `.env` file based on [`template.env`](template.env) and [set your secret key](https://platform.openai.com/docs/quickstart/step-2-set-up-your-api-key)
