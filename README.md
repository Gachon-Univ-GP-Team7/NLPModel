# NLPModel
문장 분류를 위한 다중 클래스 분류 레포지토리 입니다.

1. Python Version
  - Python 3.8 
3. Packages
  - Keras
  - genshim Word2Vec
  - Konlpy
4. Final Model
  - DL Model: ./Model/Model_final.h5
    - Keras Model
  - Embedding Model: ./Model/EmbeddingModel2.model

5. Model Data Structure
  - X_Data
    - 100x39 demension Vector
  - Y_Data
    - Age (3 ~ 10)

6. How to Install
``` 
git pull https://github.com/Gachon-Univ-GP-Team7/NLPModel.git
pip install -r requirements.txt
```
# 7. How to Use

   1. Preprocessing 
      - Need dataset formatted like ./Data/TrainData.csv
      - In WordEmbedding.ipynb -> Change target Dataset(In last Cell)
      
          ```
            train_data = pd.read_csv('/content/drive/MyDrive/Project/NLPModel/Data/{Your_Dataset}.csv')
          ```
      - In DataParser.ipynb -> Using result from WordEmbedding parsing data
