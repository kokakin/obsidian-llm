source - https://github.com/oobabooga/text-generation-webui
tags - #API #local

This tool generates it's own server locally with many functionalities built-in and a way to use it as an API;

It has been since updated to be able to use EXLlamaV2 as a loader for some models, being very fast inference compared to alternatives.

- How to install:
	- Clone the repo;
	- Access the repo directory;
	- Create and set a #pyenv virtualenv on the directory with the associated python version required;
	- Run the installation file inside the directory (this depends on the OS);
	- It will install all the requirements and start the app;
- To run:
	- Use the same file that was used to install;
	- Open the http://localhost:7860 (usually);
	- If this is the first time no models will be available. To download use the models tab and download from TheBloke (usually) https://huggingface.co/TheBloke;
		- Then under "Download model or LoRA" input the repo like "TheBloke/CodeLlama-7B-Instruct-GPTQ" without quotes;
		- After download it should appear on the select model;
	- Select your model and click load (you can adjust the settings first, usually it auto selects, but prefer to use ExLlamav2_HF);
	- After it is loaded go back to Chat
		- Select Chat-instruct and use the prompt to customize the way it works;



