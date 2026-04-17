# colab



!pip install colab-xterm
%load_ext colabxterm
%xterm

apt install screen zstd

screen
curl -fsSL https://ollama.com/install.sh | sh
ollama serve

ctrl+A ctrl+D # to switch from this terminal screen to main one
screen -r # you can use this to reenter or reattach to ollama serve screen

# in main screen run this it will talk to ollama serve screen and get it done and ready
ollama pull gemma4:latest
ollama run gemma4:latest

Ask your questions in termnial 
