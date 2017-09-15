# feel-br-headlines

# Sobre
Projeto realizado para a disciplina de pós-graduação __IA369Y - Computação Afetiva__ oferecida pela Faculdade de Engenharia Elétrica (FEEC) da Universidade Estadual de Campinas (UNICAMP), lecionada pela professora Paula Dornhofer Paro Costa. 

### Aviso

Este projeto tem como objetivo explorar possibilidades de processamento de linguagem natural para o português brasileiro. Todas as abordagens visam maximizar o aprendizado e a compreensão dos métodos utilizados, e não a performance.

# Introdução

Duas propostas foram disponibilizadas para esse projeto, a de classificar valência de manchetes brasileiras disponibilizadas em um conjunto de dados e a de atribuir intensidade de diferentes sentimentos a manchetes americanas.
<br>A primeira opção foi a escolhida pelos autores devido à sua complexidade relacionada à diminuta disponibilidade de corpus e referências para o processamento de linguagem natural no idioma Português Brasileiro.
<br>Com isso, este projeto tem como objetivo servir como uma referência básica para o processamento de linguagem natural em português, utilizando como uma alternativa viável a tradução para o inglês, já que para manchetes curtas e sentenças simples a tradução é mais do que adequada, sem comprometer o sentimento geral na maioria dos casos.
    
Além das dificuldades impostas pelo idioma, existe uma dificuldade inerente à tarefa de analisar valência em manchetes, já que elas são idealmente imparciais, dado o comprometimento ético e com neutralidade que a mídia jornalística deveria apresentar. Por outro lado, ao julgar a valência da manchete, o leitor tipicamente associa seu conteúdo às suas vivências anteriores e visão de mundo.  
    
Esse projeto apresenta diferentes abordagens para o processamento de linguagem natural em português, bem como os pontos fortes e fracos de cada uma das abordagens utilizadas neste projeto. Por fim, também são apresentadas abordagens para um classificador de origem do jornal e análises de qual das publicações obteve resultados mais neutros.

## How To Run
One approach to run this project is to load the available environment using conda. To do so, just run: 
	conda env create -f environment.yml
	source activate textAdventures (LINUX)
	activate textAdventures (Windows)
Another approach is to manually install the dependencies, which are
jupyter, nltk, pandas, matplotlib, numpy, os, sys, googletrans, TextBlob, re, scipy, sklearn

From the nltk library, the user needs to download:
	stopwords, wordnet, sentiwordnet and vader_lexicon
Additionally, the user needs to download:
	The SentiLex lexicon at http://xldb.fc.ul.pt/wiki/SentiLex-PT01
	The headlines database: https://github.com/pdpcosta/manchetesBrasildatabase