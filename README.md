Installation

The complete build of this program is too large to be committed, the user must run this program using python 3.12


install ollama from https://ollama.com/download

download the required model llava:7b (https://ollama.com/library/llava:7b)
add ollama to system PATH

by running the follwoing command in command prompt:
ollama pull llava:7b

install all required library using the following command:

pip install -r requirements.txt


run the python file main.py

the value in _config.py may be changed by the user to tune out how the models response or resources accessed by the program

user must input a video via windows explorer to continue

all the results files will be automatically generated once the analysis is done (make take very long time)
