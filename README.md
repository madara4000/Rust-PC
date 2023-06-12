# Rust-PC
//=comentarios
baixar esse arquivo e descompactar ou dar git clone pelo git 
passo a passo para instalção do Kernel
 baixar jupyter notebook
0. instalar pithon e baixar jupyter por ele
1. instalar o mini conda ou anaconda //https://docs.conda.io/en/latest/miniconda.html ou https://www.anaconda.com/download
2. adicionar o conda ao Path( nas variaveis de ambiente)
3. baixar e instalar rust na maquina passo a passo abaixo//https://www.rust-lang.org/learn/get-started
4. instalar nodeJS //https://nodejs.org/en/download
5. adicionar cargo no PATH(variaveis de ambiente)
6. conda create -n name  //name é um nome a escolha só não esqueçam ele pois ele será onde será instalado kernel do jupyter para ser compativel com Rust
7. conda activate name 
8.  shahin$ // comando para ver se existe
9. shahin$ jupyter lab //verifica se o jupyter lab está instalado
10. execute no terminal conda install -c conda-forge jupyterlab
11.  execute no terminal  conda install -c anaconda cmake -y
12.  conda install -c conda-forge nodejs=15 -y
13.  execute no terminal  jupyter labextension install jupyterlab-plotly
14. execute no terminal  jupyter labextension install @shahinrostami/theme-purple-please
15. cargo install evcxr_jupyter --version 
16. evcxr_jupyter --install
17. jupyter notebook
18.  vai nas pastas baixadas dentro do jupyter

