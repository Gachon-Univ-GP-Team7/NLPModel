## 1 Python Version
  - Python 3.8 
## 2 Packages
  - Keras
  - genshim Word2Vec
  - Konlpy
## 3 Final Model
  - DL Model: ./Model/Model_final.h5
    - Keras Model
  - Embedding Model: ./Model/EmbeddingModel2.model

## 4 Model Data Structure
  - X_Data
    - 100x39 demension Vector
  - Y_Data
    - Age (3 ~ 10)

## 6 How to Install
  ``` 
  git pull https://github.com/Gachon-Univ-GP-Team7/NLPModel.git
  pip install -r requirements.txt
  ```
## 7. How to Use

   1. Preprocessing 
      - Need dataset formatted like ./Data/TrainData.csv
      - In WordEmbedding.ipynb -> Change target Dataset(In last Cell)
      
          ```
            train_data = pd.read_csv('/content/drive/MyDrive/Project/NLPModel/Data/{Your_Dataset}.csv')
          ```
      - In DataParser.ipynb -> Using result from WordEmbedding parsing data
       - Change parsing target Embeding Data
          ```
            data = pd.read_csv('/content/drive/MyDrive/Project/NLPModel/Data/{Your_Embedding_Data}.csv'')
          ```
   2. Train Model
   - In Keras_classification.ipynb -> train model from zero-base
   - Just change target data
      ```
      data = pd.read_csv('./Data/{Your_Embedding_Data}.csv')
      ```

## 8 Contributor
  - 이지호
    https://github.com/destiny3912
  - 김윤정
    https://github.com/yunjjung
