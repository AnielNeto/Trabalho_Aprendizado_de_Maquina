![Local Image](Imagens/Cabecalho.png)


<div align="center">
  <H1>Aprendizado de Máquina - Trabalho Final</H1>
  <H3>Prof.º Daniel Roberto Cassar</H3> 
</div>

<br>

<div align="right">
  <H3>Guilda: Carcajus</H3>
  <H4>Aniel Souza Ribeiro Neto</H4>
  <H4>Caio Cogo Beriam</H4>
  <H4>Joaquim Junior Ferola Fonseca</H4>
</div>

<br> 

<div align="center">
  <img src="Imagens/carcajus_bg.png" width="500"/>
  <figcaption><H3><I>"Mastigar primeiro, digerir depois!"</I></H3></figcaption>
</div>

# 📜 Introdução 

Repositório para o trabalho final da disciplina Aprendizado de Máquina do curso de graduação em Ciência e Tecnologia da Ilum Escola de Ciência.

O trabalho consiste no estudo de algoritmos de aprendizado de máquina e tratamento de dados para previsão da toxicidade de nanopartículas com base em suas caracteríticas. A área de nanotoxicologia, que estuda como nanomateriais interagem com sistemas biológicos, tem se tornado cada vez mais importante com os avanços da nanotecnologia, permitindo que esses materiais sejam implementados de maneira segura ao meio ambiente e aos possíveis seres vivos que venham a entrar em contato com esses nanomateriais. Entretanto, como outras características dos nanomateriais, sua toxicidade pode variar muito conforme a morfologia do composto, assim, para ser analisada corretamente uma série de fatores devem ser levados em consideração, o que torna difícil a previsão da toxicicidade dos materiais. 

Sob essa perspectiva, nosso trabalho tem o objetivo de facilitar esse trabalho através do treinamento de um modelo de Aprendizado de Máquina Supervisionado capaz de prever  se uma nanopartícula é tóxica com base em características da sua morfologia. Para isso, utilizaremos como base um conjunto de dados contendo as características de diversas nanoparticulas e se elas são ou não tóxicas. O dataset foi elaborado pelo trabalho Subramanian NA, Palaniappan A. NanoTox: Development of a Parsimonious In Silico Model for Toxicity Assessment of Metal-Oxide Nanoparticles Using Physicochemical Features. ACS Omega 2021, 6, 17, 11729–11739 doi:10.1021/acsomega.1c01076, e o obtivemos pela plataforma Kaggle através do endereço https://www.kaggle.com/datasets/apalania/toxicityassessment-meoxnp.

# 📁 Conteúdos do Repositório

Esse repositório contém todos os códigos, dados e resultados obtidos, seguindo uma licensa de uso GNU GENERAL PUBLIC LICENSE 3.0. 
* 📄Trabalho Aprendizado de Maquina.ipynb: Jupyter notebook contendo os códigos para tratamento dos dados, treino dos modelos, optimização de hiperparâmetros e teste dos modelos;
* 📊nanotox_dataset.tsv: Dataset utilizado na forma de dados separados por tabulação;
* 📊Estudo KNN.db: Estudo do optuna contendo os dados obtidos pela optimização dos parâmetros de um modelo K vizinhos mais próximos;
* 📊Estudo SVC.db: Estudo do optuna contendo os dados obtidos pela optimização dos parâmetros de um modelo de Máquina de vetores suporte;
* 📊Estudo LRC.db: Estudo do optuna contendo os dados obtidos pela optimização dos parâmetros de um modelo de Regressão Logística;
* 📊Estudo DTC.db: Estudo do optuna contendo os dados obtidos pela optimização dos parâmetros de um modelo de Árvore de Decisão de Classificação;
* 📊Estudo RFC.db: Estudo do optuna contendo os dados obtidos pela optimização dos parâmetros de um modelo de Floresta Aleatória de Classificação;
* 📂Imagens: Pasta contendo imagens de apoio utilizadas no notebook e readme.

# ❓Como utilizar o repositório

Para utilizar esse trabalho por completo será necessário possuir acesso a uma aplicação capaz de rodar notebooks jupyter e com os módulos nele indicados instalados. É recomendado que sejam baixados todos arquivos do repositório para a melhor experiência, deixando todos os arquivos do repositório na mesma disposição ao utilizar o notebook. Os arquivos nomeados "Estudo {Sigla do Modelo}.db" são opicionais, servindo para praticidade e arquivo dos resultados da optimização de hiperparâmetros do trabalhos evitando que o leitor tenha de refazer esse processo ou que não obtenha os mesmos resultados exatamente como apresentados no trabalho, dessa forma, caso seja de desejo do leitor, podem ser ignorados, mas mantendo em mente que as otimizações terão de ser refeitas caso o código seja rodado.
