# Mundo 3 - Como instalar o Python

> ## **O que é linguagem de programação**

Uma linguagem de programação é um conjunto de regras sintática e semântica para implementar um código fonte.

Toda linguagem de programação é convertida em binários (0 ou 1), pois é a forma que o computador entende.

Essa conversão é um processo intermediário realizado por outro programa para traduzir o código fonte em linguagem de máquina e que pode variar entre um processo de compilação ou interpretação.

Além disso, exitem ferramentas para facilitar o desenvolvimento, como por exemplo o Jupyter Notebook, VS Code, PyCharm, etc.

> ## **Instalação Linux**

1. Instalação do gerenciador de pacotes no Python, PIP:

   ```shell
   $ sudo apt install python3-pip
   ```

2. Instalação de pacotes: pandas, numpy, matplotlib:

   ```shell
   $ pip3 install pandas matplotlib
   ```

   > **OBS**: o pacote `numpy` ´e instalado automaticamente ao instalar o `pandas`

3. Instalação da IDE Jupyter Notebook:

   ```shell
   $ pip3 install jupyter
   ```

4. Executar a IDE Jupyter Notebook:

   ```shell
   $ python -m notebook
   ```
