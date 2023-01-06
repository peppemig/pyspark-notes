## PySpark Notes

-- pyspark-1.ipynb
- come creare SparkSession
- come leggere data set e settare header
- check type e Schema
- funzione .head() per prendere solo un determinato range di righe


-- pyspark-2.ipynb
- inferSchema -> assegnare data type corretti alle colonne
- selezionare una colonna o colonne multiple
- check data types
- funzione .describe() -> ci da in automatico count, mean, stddev, min, max
- aggiungere colonne - .withColumn()
- eliminare colonne - .drop()
- rinominare colonne - .withColumnRenamed()


-- pyspark-3.ipynb
- come eliminare valori null - na.drop()
- parametri "how" e "subset" di na.drop()
- come fare fill di valori null - na.fill()
- imputer


-- pyspark-4.ipynb
- filter operations
- inverse operations -> ~


-- pyspark-5.ipynb
- groupBy operations
- aggregate operations


-- pyspark-6.ipynb (ERRORE)
- esempio prediction tramite ML - valori errati (penso per data set troppo piccolo)


-- pyspark-7.ipynb
- IMPLEMENTAZIONE REGRESSIONE LINEARE
- ESEMPIO PREDICT TRAMITE ML
  (predict conto ristorante in base a varie features)
  (errore assoluto medio 4.56)





