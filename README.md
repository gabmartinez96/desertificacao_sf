# gee-python

## Setup local

1. Crie o ambiente a partir de `environment.yml` com Python 3.11.
2. Selecione esse ambiente como kernel do notebook no VS Code/Jupyter.
3. Coloque o arquivo `bacias_meso_SF.geojson` em `data/raw/`.
4. Faça a autenticação do Google Earth Engine na primeira execução do notebook.
5. Abra `scripts/1-MSAVI_Test.ipynb` e execute as células em ordem.

## Observações

- O notebook foi ajustado para rodar fora do Colab.
- O caminho local esperado para a camada vetorial é `data/raw/bacias_meso_SF.geojson`.
- O arquivo `requirements.yaml` é um export de ambiente em UTF-16 e não é o caminho principal de setup.