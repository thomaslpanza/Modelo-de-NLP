# Modelo-de-NLP
----

Foi criado um modelo de classificação de sentimento à partir de uma base de dados utilizando tweets, divididos em sentimentos negativos, positivos e neutros.

Os textos tratados incialmente retirando a acentuação, textos e alteração de emojis, além de se retirar as "stopwords". Após isso foram criadas wordclouds para se analisar as palavras que mais se destacaram em cada sentimento.

Em seguida foram utilizadas as ferramentas Count-Vectorizer, TF-IDF e Word2Vec para criação as features. A partir daí foram utilizadas a regressão logística, Decision Tree, Random Forest e AdaBoost para criação de modelos para cada uma delas. Na maioria dos casos a regressão logística apresentou melhores métricas de classificação. Buscou-se otimizar o modelo de Random Forest criado à partido do TF-IDF para verificar se seria possível conseguir um modelo mais assertivo que a regressão logística, mas sem sucesso.
