- Per eseguire il test sul classificatore già addestrato:
	* Inserire il file contenente il test set in questa cartella	
	* Aprire il file testing_routine.ipynb	
	* Modificare la variabile test_filename iserendo il nome del file di test
	* Caricare il file di test, preprocessing.joblib e classificator.joblib	nello spazio di archiviazine di sessione di colab
	* Procedere alla normale esecuzione.
- Nel file traininig_routine.ipynb è presente il codice utilizzato per il preprocessing e addestramento del modello
        NOTA: nel caso si voglia eseguire il traininig bisogna caricare il file con il dataset di train nello spazio di archiviazione di sessione
              di colab poi eseguire normalmente. I file di preprocessor e classificator serializzati verranno memorizzati temporaneamente
              nello spazio di archiviazione di sessione e da lì potranno essere scaricati se necessario.
- I file preprocessing.joblib e classificator.joblib contengono, serializzati, il preprocessing ed 
  il classificatore addestrato