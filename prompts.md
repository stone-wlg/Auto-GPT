# Usage
```sh
$ docker build -t stonewlg/auto-gpt:1.0 .
$ docker run -it --env-file=./.env -v $PWD/auto_gpt_workspace:/home/appuser/auto_gpt_workspace stonewlg/auto-gpt:1.0
```

# Prompts
```txt
AI Name: "Text to SQL"
AI Description: "Translate text to SQL using Hugging Face transformers"
Goal1: "Translate text to SQL"
Goal2: "Use Hugging Face transformers"
Goal3: "Use SQL"
Goal4: "Use GPT"
Goal5: "Python Example"
```
```txt
AI Name: "AutoGPT-Demo"
AI Description: "an ai designed to teach me about auto gpt"
Goal1: "search auto gpt"
Goal2: "find the github and figure out what th e project is"
Goal3: "explain what auto gpt is in a file named autogpt.txt"
Goal4: "terminate"
```