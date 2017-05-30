Iniciar o servidor redis em /usr/local/bin  $ redis-server
redis-cli config set notify-keyspace-events KAE

Linux: dentro do diretório do projeto
pip install virtualenv
virtualenv -p python3 venv
. venv/bin/activate -> inicializar ambiente virtual
pip install -r requirements.txt