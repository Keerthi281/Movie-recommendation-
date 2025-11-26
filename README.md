 Dataset Information

The dataset used in this project is *not included* in this repository.  
You can use *any movie rating or user–item interaction dataset* for collaborative filtering.

### ✔ Requirements for the dataset
Your dataset should contain at least these columns:

- *user_id* – Unique ID for each user  
- *item_id / movie_id* – Unique ID for each movie or item  
- *rating* – User’s rating or preference score  

Example structure:

user_id | movie_id | rating  
--------|----------|--------  
1       | 10       | 4  
1       | 22       | 5  
2       | 10       | 3  
2       | 33       | 4  

### ✔ Supported datasets  
You can use any dataset suchas:

- *MovieLens* (highly recommended)  
- Kaggle movie rating datasets  
- Your own custom dataset  

### ✔ Just change the dataset path  
This project is *not tied to any specific dataset*.  
You only need to update the file path in the code:
### python
 df=pd.read_csv("your_dataset.csv")

```python
df = pd.read_csv("your_dataset.csv")
