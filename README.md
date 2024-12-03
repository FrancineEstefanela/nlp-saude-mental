### **Objetivo do Projeto**

Desenvolver um modelo de Machine Learning para analisar postagens em fóruns online sobre saúde mental e identificar sinais potenciais de risco de suicídio, com o objetivo de auxiliar na prevenção e intervenção precoce. Projeto realizado para disciplina de IA na Saúde

### **Sobre o Projeto**
 
A crescente popularidade de fóruns online como o Reddit trouxe à tona um desafio importante: identificar postagens que possam indicar sinais de transtornos mentais. Embora esses espaços sejam essenciais para conectar pessoas e compartilhar experiências, o volume de dados e a complexidade da linguagem dificultam a detecção de sinais de alerta.

A identificação manual de postagens relacionadas à saúde mental é uma tarefa árdua e ineficaz, especialmente para moderadores e profissionais da área. Esse projeto visa automatizar a análise dessas postagens, facilitando a triagem e oferecendo suporte para intervenções mais rápidas e eficazes.

Com isso, buscamos melhorar a identificação de indivíduos que possam precisar de ajuda e apoio em momentos de vulnerabilidade.

### **Tecnologias e Ferramentas**

Para organizar o desenvolvimento deste projeto, utilizei o método CRISP-DM (Cross-Industry Standard Process for Data Mining), um guia passo-a-passo amplamente utilizado em projetos de ciência de dados, que me ajudou a seguir todas as etapas importantes, desde o entendimento do problema até a análise dos resultados.

* **Processamento de Linguagem Natural (PLN):** Preparação do texto, transformação em números para análise de ML.
* **Regressão Logística:** Modelo utilizado para classificar postagens relacionadas a transtornos mentais.
* **NLTK:** Para pré-processamento de texto.
* **Scikit-learn:** Para treinamento do modelo de ML.
* **Pandas:** Para manipulação dos dados.
* **Matplotlib/Seaborn:** Para visualização dos resultados.

### **Sobre o Dataset**
O dataset `mental_disorders_reddit.csv` contém postagens do Reddit sobre saúde mental, com informações como título, texto, data de criação, NSFW e subreddit. O objetivo é usar essas informações para classificar postagens e detectar sinais de risco.

[Link para o dataset do Kaggle](https://www.kaggle.com/datasets/kamaruladha/mental-disorders-identification-reddit-nlp?resource=download)

<img src="Monitoramento_Sentimentos_Posts.png" alt="Monitoramento de Sentimentos" width="500" />

