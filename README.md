# data-engineering

Este projeto é configurado como um projeto Python padrão.
Para criar o virtualenv, ele pressupõe que haja um executável python3 (ou python para Windows) em seu caminho com acesso ao pacote venv.
Neste exemplo, estaremos executando numa máquina windows.
### 1 - Criar o ambiente virtual:

```py
python -m venv .venv
```

### 2 - Ativar o ambiente virtual: 

```py
.venv\Scripts\activate.bat
```

Assim que o virtualenv for ativado, você pode instalar as dependências necessárias.

### 3 - Instalar as dependências: 

```py
pip install -r requirements.txt
```

Neste ponto, você pode executar o script etl.py.
Ele criará o arquivo TotalCost.xlsx no diretório atual.
### 4 - Execute o script etl.py: 

```py
etl.py
```

Enjoy!
