# Inteli - Instituto de Tecnologia e Liderança

<p align="center">
<a href= "https://www.inteli.edu.br/"><img src="https://www.inteli.edu.br/wp-content/uploads/2021/08/20172028/marca_1-2.png" alt="Inteli - Instituto de Tecnologia e Liderança" border="0"></a>
</p>

# Nome do projeto

## GCPI
<p align="center">
<a href= ""><img src="https://img.ibxk.com.br/2022/08/25/25111252644077.jpg" alt="Inteli - Instituto de Tecnologia e Liderança" border="0" width="600"></a>
</p>

## Integrantes:
- <a href="https://www.linkedin.com/in/felipe-saadi">Felipe Saadi</a>
- <a href="https://www.linkedin.com/in/felipe-sampaio-silva">Felipe Sampaio</a>
- <a href="https://www.linkedin.com/in/gabriel-pascoli-73733b200">Gabriel Pascoli</a>
- <a href="https://www.linkedin.com/in/leandro-custodio">Leandro Custódio</a>
- <a href="https://www.linkedin.com/in/pablo-ruan-lana-viana">Pablo Ruan</a>
- <a href="https://www.linkedin.com/in/pedro-silva-14343022a">Pedro Silva</a>
- <a href="https://www.linkedin.com/in/rafael-moritz">Rafael Moritz</a>

## 📝 Descrição
A Rappi identificou um problema em que uma quantidade considerável de entregadores abandonavam a plataforma (churn), dessa forma o trabalho da equipe foi entender quais as principais causas/motivos das saídas da empresa, através de dados disponibilizados pela empresa. A partir disso, desenvolver um modelo preditivo para apresentar a probabilidade de um entregador deixar o aplicativo e assim ajudar no controle de recursos da Rappi.
.

## 📁 Estrutura de pastas

|--> documentos<br>
  &emsp;| Documento_sprint1.docx<br>
  &emsp;| Documento_sprint2.docx<br>
  &emsp;| Documento_sprint3.docx<br>
  &emsp;| Documento_sprint4.docx<br>
  &emsp;| Documento_sprint5.docx<br>
|--> src<br>
  &emsp;|--> Colab_Efetivo.ipynb<br>
  &emsp;|--> Colab_Treino.ipynb<br>
| readme.md<br>


Dentre os arquivos presentes na raiz do projeto, definem-se:

- <b>readme.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

- <b>documentos</b>: aqui estarão todos os documentos do projeto, com as versões de cada uma das sprints.

- <b>src</b>: nesta pasta encontra-se o código realizado, em formato .ipynb. Um dos arquivos corresponde ao script de treinamento e o outro ao de deploy.


## 💿 Instruções de uso
O usuário deverá acessar o seguinte link do Google Drive: https://drive.google.com/drive/u/1/folders/1QAwfG64_h2sMujFuwDWvDGpFChBoHal9

Ao acessar essa pasta pela primeira vez, o usuário deverá criar um atalho diretamente para o MyDrive, a partir do comando ilustrado seguinte imagem:

<a href= ""><img src="https://ik.imagekit.io/wfexexpan/Captura_de_tela_2022-10-06_014511_3QMrz62cT.png?ik-sdk-version=javascript-1.4.3&updatedAt=1665031571483" alt="Add shortcut to Drive" border="0" width="300"></a>

A pasta irá conter os seguintes itens:

- <b>bases</b>: Nessa pasta se localizam as bases de dados que o cliente deverá fazer o upload, sempre com o mesmo nome indicado, para não haver erro de execução do script.

- <b>modelos</b>: Nessa pasta se localizam os modelos treinados, executados pelo Colab_Treino

- <b>Colab_Treino</b>: Esse será o Colab responsável por conter as informações e códigos para o treinamento dos modelos, e deve ser utilizado caso houver a necessidade de alteração de algum elemento do treinamento, mas o cliente não precisa interagir com esse arquivo (deve ser utilizado por desenvolvedores).

- <b>Colab_Definitivo</b>: Esse será o Colab utilizado pelo cliente para realizar a utilização da solução (interface produto-cliente).

Quando for necessário fazer uma atualização da base de dados, será necessário fazer o upload das seguintes tabelas dentro da pasta "bases", contendo as respectivas colunas:

Distance.csv: Tabela com a distância percorrida a cada pedido

Incidentes_Regras RT.csv: Tabela contendo informações sobre punições 

infos gerais.csv: Informações sobre o RT

Orders Done e Cancel.csv: Tabela com os pedidos entregues e cancelados


Ao abrir o arquivo Colab_Definitivo, o usuário encontrará a seguinte interface: 

<a href= ""><img src="https://ik.imagekit.io/wfexexpan/Captura_de_tela_2022-10-06_103257_eOAsoIZJj.png?ik-sdk-version=javascript-1.4.3&updatedAt=1665063206642" alt="Add shortcut to Drive" border="0" width="300"></a>

Será necessário realizar a escolha de qual será o objetivo da aplicação do modelo.

Após isso, é preciso pressionar o botão sinalizado em verde na imagem, para iniciar o deploy.

Caso obter sucesso, sera possível exportar a tabela em formato csv ou xlsx, sendo adicionada na pasta do projeto.

## 🗃 Histórico de lançamentos
* 0.6 - 05/10/2022
    * Alterações na interface de visualização do projeto
    * Melhorias na interface de uso (instruções e comentários)
* 0.5 - 22/09/2022
    * Utilização de hiperparâmetros nos modelos selecionados
    * Uso da ferramenta Pycaret
* 0.4 - 09/09/2022
    * Criação dos modelos
    * Seleção dos melhores algoritmos
    * Ajuste nas features
* 0.3 - 25/08/2022
    * Criação e seleção das features
    * Elaboração da Persona
    * Preparação dos dados para treino
* 0.2 - 12/08/2022
    * Análise da Indústria
    * Análise Externa do Mercado
    * Início do Tratamento de dados
    * Solicitação de tabelas complementares
* 0.1 - 01/08/2022
    * Início do Projeto

## 📋 Licença/License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/Spidus/Teste_Final_1">MODELO GIT INTELI</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://www.yggbrasil.com.br/vr">Inteli, Felipe Saadi, Felipe Sampaio, Gabriel Pascoli, Leandro Custódio, Pablo Ruan, Pedro Silva, Rafael Moritz</a> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>

## 🎓 Referências

Aqui estão as referências usadas no projeto:

1. <https://scikit-learn.org/stable/>
2. <https://pandas.pydata.org/>
3. <https://colab.research.google.com/>
4. https://www.rappi.com.br/
5. https://pycaret.org/
6. https://stackoverflow.com/
