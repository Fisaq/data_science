# Modelo de Previsão de Falhas em Motores Elétricos

Este projeto, é um dos 5 projetos sugeridos pelo @Meigarom, do canal **Comunidade DS**. Em seu blog no Medium, Seja um Data Scientist, 
ele sugere 5 projetos essenciais para compor o portfólio de qualquer Cientista de Dados, ou aspirante a Cientista de Dados.

O objetivo do projeto de Machine Learning é criar uma solução de negócio usando um algoritmo de Machine Learning.

O projeto do tipo Machine Learning cobre 6 passos do roadmap de resolução de problemas em Data Science, sendo esses: Coleta de Dados, Limpeza de Dados, Exploração de Dados, Modelagem de Dados, Aplicação de algoritmos de Machine Learning e Métricas de Performance.

# Sobre o projeto

Você é um Data Scientist contratado por uma empresa chamada Rocket Science Inc, uma multinacional que produz peças para a construção de satélites. As peças são produzidos por uma fábrica com 18 linhas de produção.

O sucesso da empresa Rocket Science Inc é diretamente relacionado ao tempo em que as máquinas permanecem operando, ou seja, as máquinas não podem ficar fora de operação, quebradas aguardando manutenção.

Para garantir o funcionamento ininterrupto das máquinas, o time de manutenção realiza manutenções periódicas programadas, a fim de substituir peças gastas, lubrificar as partes móveis e checar a vida útil de motores elétricos, tudo isso para evitar a quebra repentina

Como um Data Scientist, **você foi contratado pela Rocket Science Inc. para prever quando ocorrerá a falha em um motor elétrico**

# Características do Conjunto de Dados

Para esse desafio, vamos usar os arquivo “RUL_FD001.txt”, “train_FD001.txt” e “test_FD001.txt”.

O arquivo “train_FD001.txt” possui 26 colunas

![image](https://github.com/Fisaq/data_science/assets/95030412/98ab551c-a32b-4567-950d-707a33f93ae4)

Cada linha desse conjunto de dados representa 1 ciclo de medições. As medições são feitas por 21 sensores e 3 valores de ajuste, como descrito nas colunas.

Cada motor possui um ciclo máximo de medição, após esse ciclo máximo é esperado um número de ciclos até a falha do motor. Esse número de ciclos esperados até a falha é chamado de RUL ( Remaining Useful Life ).

Por exemplo, o número máximo de ciclos do motor 01 é 192, como descrito na imagem abaixo. Após o ciclo 192, é esperado 112 ciclos até a falha.


![image](https://github.com/Fisaq/data_science/assets/95030412/ac6d5014-60b7-4d62-a567-fc44a96f4eea)


O valor 112 é o número de ciclos esperados até a falha ( RUL ). Esse valor pode ser encontrado no arquivo “RUL_FD001”, como na figura abaixo.

![image](https://github.com/Fisaq/data_science/assets/95030412/81345897-aaff-4ced-97f5-bebae62dfa0e)

A primeira linha mostra um valor de 112 para RUL. Esse valor corresponde ao número de ciclos estimado, até a falha, para o motor 01.

A segunda linha mostra um valor de 98 para RUL, que corresponde ao número de ciclos estimado, até falha, para o motor 02. E assim por diante.

O seu objetivo como Data Scientist é prever o valor do RUL para os motores do conjunto de dados de teste “RUL_FD001.txt” e responder à essa pergunta:

### Quantos ciclos cada motor ainda possui até a falha?


# Resolução e Tecnologias Utilizadas

| Base de Dados | Ambiente | Linguagem | Resolução |
|---------------|----------|-----------|-----------|
| [The Prognostics Data Repository](https://www.nasa.gov/intelligent-systems-division/discovery-and-systems-health/pcoe/pcoe-data-set-repository/) | Jupyter Notebook | Python | [Diretório](exemplo.com.br) |
