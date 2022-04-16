# Projeto: Pacote de Processamento de Imagens
## Autora: Karina Kato
### Descomplicando a criação de pacotes de processamento de imagens em Python - Digital Innovation One
#### Linguagem: Python
#### Data: 15/04/2022
-----------------------------------------
## Descrição
O pacote "image_processing-test" é utilizado para:

- Processing:
  - Correspondência de histograma;
  - Similaridade estrutural;
  - Redimensionar imagem;

- Utils:
  - Ler imagem;
  - Salvar imagem;
  - Plotar imagem;
  - Resultado do gráfico;
  - Plotar histograma;
---------------------------------------------
## Instalação

- [x] Instalção do Pacote

Use o gerenciador de pacotes ```pip install -i https://test.pypi.org/simple/ image-processing-test ```para instalar image_processing-test

```bash
pip install image-processing-test
```
- [x] Instalação de dependências
```
pip install -r requirements.txt
```
-------------------------------------------------
## Exemplo de uso

```python
from image-processing-test.processing import combination
combination.find_difference(image1, image2)
```
## Autora do Projeto
Karina Kato
## Editor (hospedou o projeto no Test Pypi)
Maycon Mota

## Licença
[MIT](https://choosealicense.com/licenses/mit/)
