# Imersão Dev Agentes de IA Google

## Rodando no Google Colab
É necessário adicionar sua chave api Gemini para iniciar o programa. Deve se ir na aba Secrets, adicionar novo secret, nomear como 'GEMINI_API_KEY' e inserir o valor da chave.

Para ter acesso aos pdfs, deve ser feito o upload na aba de "Arquivos".

## Rodando localmente
Para iniciar o programa localmente, deve-se instalar a dependência para o Python Notebook:

```
pip install --upgrade ipykernel
```

Dependendo, deve ser necessário iniciar um ambiente virtual primeiro. Caso esse for o caso, esse comando deve ser usado antes do anterior:

```
# instala e inicia o ambiente virtual
python -m venv .venv
source .venv/bin/activate
```

Além disso, deve ser criado um arquivo .env seguindo a estrutura do arquivo '.env.example', onde estará guardada a chave da API.