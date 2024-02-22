# Horário acadêmico IFRN Parnamirim

Horário publicado em: <https://mange.ifrn.edu.br/horario/parnamirim/>

## Criação de ambiente virtual

Abra um terminal (Linux, WSL ou Mac) no diretório onde se encontra este arquivo (`README.md`) e execute os seguintes comandos:

1. `python3 -m venv .venv`
2. `source .venv/bin/activate`
3. `pip3 install -r requirements.txt`

## Geração da documentação

Execute os seguintes comandos, na sequência:

1. `make clean`
2. `make html`

Caso o último comando tenha apresentado alguma mensagem de erro, que costuma aparecer de cor laranja, corrija-o antes de visualizar o documentação gerada.

## Visualização da documentação

1. Entre no diretório `docs/_build/` e inicie o servidor HTTP do módulo `http.server` do Python. Execute:

   - `(cd docs/_build/html && python -m http.server)`;

2. Abra a URL <http://localhost:8000>;
3. Pare o servidor HTTP pressionando as teclas <kbd>Ctrl`</kbd>+<kbd>C</kbd>.

