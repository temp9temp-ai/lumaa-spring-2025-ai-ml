# AI/Machine Learning Intern Challenge: Simple Content-Based Recommendation

**Deadline**: Sunday, Feb 23th 11:59 pm PST

---

## Overview

Build a **content-based recommendation system** that, given a **short text description** of a user’s preferences, suggests **similar items** (e.g., movies) from a small dataset. This challenge should take about **3 hours**, so keep your solution **simple** yet **functional**.

### Example Use Case

- The user inputs:  
  *"I love The story of Batman and Joker."*  
- Your system processes this description (query) and compares it to a dataset of items (e.g., movies with their plot summaries or keywords).  
- You then return the **top 3–5 “closest” matches** to the user.

---

1. **Dataset**: movies2.csv is the collected (movie name, plot) pairs, 94 rows
2. **Setup**:
   - I strongly recommend you to use Kaggle,
   - upload the movies2.csv as a database in Kaggle (let's name this database as movie_data),
   - start a notebook and paste the code within **clear-ok-tf-idftext.ipynb** then add the movie_data as your input dataset,
   - then you would just put the run button on the left side of the code, without the worries about the running environment.
4. **Running**:
   - After you set up as mentioned, you are now in Kaggle and have the codes and dataset, in the codes notebook
   - Change the dataset path to your Kaggle path, e.g., `file_path = '/kaggle/xxx/movies2.csv'`
   - Change the query as you like, e.g., `user_query = "I love The story of Andy Dufresne."`
   - Then you could just run it! You will get five movies which are the Most Relevant Movies with the corresponding cosine similary scores.
5. **Results**:
   the query is "I love The story of Andy Dufresne.", I will get the following results:
   - `Recommended Movies Based on Your Preferences:`
   - `Title: The Shawshank Redemption, Similarity: 0.3225`
   - `Title: Titanic, Similarity: 0.1907`
   - `Title: Toy Story 3, Similarity: 0.1730`
   - `Title: Slumdog Millionaire, Similarity: 0.1468`
   - `Title: Her, Similarity: 0.1340`

6. **Salary expectation per month** $1000~$1500/month for internship

7. **Short Video Demo**
   - ![Awesome Animation](https://github.com/temp9temp-ai/lumaa-spring-2025-ai-ml/blob/main/output.gif)
