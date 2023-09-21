API: (https://github.com/20-100-oc/oc_9_serverless.git)

  azure_function:
    - folder containing all the code used for the API (serverless azure function, deployed with github)



APP:
  streamlit_app.py:
     - streamlit app that sends a request to the API and get article recommendations as a response



NOTEBOOKS: (https://github.com/20-100-oc/oc_9_scripts.git)

  CF_model.ipynb: 
    - code for collaborative filtering model

  embeddings.ipynb: 
    - code for content based model (based on last seen article, used in API)
    - code used to create the "embeddings_pca.npy" file (PCA on embeddings saved in a file, used to compute similarities of articles in API)
    - code used to create the "recs_idx_20.npy" file (pre-comuted top 20 most similar articles for every article, used for faster response in API)

  read_list.ipynb: 
    - code used to create the "time_click.pkl" file (list of read articles by every user, used to get last seen article of user in API)
 