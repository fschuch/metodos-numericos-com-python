# Métodos Numéricos com Python

Esta palestra tem por objetivo introduzir os principais conceitos de programação e Python, empregando a didática interativa da plataforma Jupyter Notebook. Além disso, demonstra-se como solucionar problemas em métodos numéricos por meio de propostas computacionais. Para tanto, o material é dividido em duas aulas:

1. [Ligeira Introdução à Python](http://nbviewer.jupyter.org/github/fschuch/metodos-numericos-com-python/blob/main/Aulas/01-Introdução-Python-Bibliotecas.ipynb), contemplando:

   - Introdução e revisão sobre conceitos de programação em Python;
   - Manipulação de tensores em Python com Numpy;
   - Produção de gráficos com o pacote Matplotlib;
   - Cálculo Diferencial e Integral com Python;
   - Resolvendo Equações Diferenciais;

2. Exemplos de aplicação em Fenômenos de Transporte (próxima semana).

## Configurando o Tutorial

Esse tutorial foi projetado para rodar no [Binder](https://mybinder.org/).
O serviço permite executar totalmente na nuvem, nenhuma instalação extra é necessária.
Para tanto, basta clicar [aqui](https://mybinder.org/v2/gh/fschuch/metodos-numericos-com-python/main?urlpath=lab):

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fschuch/metodos-numericos-com-python/main?urlpath=lab)

Se você prefere instalar o tutorial localmente, siga os seguintes passos:

1. Clone o repositório:

   ```
   git clone https://github.com/fschuch/metodos-numericos-com-python
   ```

1. Instale o ambiente. O repositório inclui um arquivo `environment.yaml` que contém uma lista de todos os pacotes necessários para executar esse tutorial.
   Para instalá-los usando conda, use o comando:

   ```
   conda env create -f environment.yml
   conda activate metodos-numericos-python
   ```

1. Inicie uma seção Jupyter:

   ```
   jupyter lab
   ```

## Sobre o Autor

> **Felipe N. Schuch**,<br>
> Pesquisador em Fluidodinâmica Computacional na PUCRS, com interesse em: Escoamentos turbulentos, transferência de calor e massa, e interação fluido-estrutura; Processamento e visualização de dados em Python; Jupyter Notebook como uma ferramenta de colaboração, pesquisa e ensino.<br>
> [felipeschuch@outlook.com](mailto:felipeschuch@outlook.com "Email") [@fschuch](https://twitter.com/fschuch "Twitter") [Aprenda.py](https://fschuch.github.io/aprenda.py "Blog") [@aprenda.py](https://www.instagram.com/aprenda.py/ "Instagram")<br>

## Licença

[BSD-3-Clause License](https://github.com/fschuch/metodos-numericos-com-python/blob/main/LICENSE).

© 2021 Felipe N. Schuch. Todos os direitos reservados.
