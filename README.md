# Movie-recommender- Using Machine learning and Django

A Web Base user-item Movie Recommendation Engine using Collaborative Filtering By matrix factorizations algorithm and The recommendation based on the underlying idea that is if two persons both liked certian common movies,then the movies that one person has liked that the other person has not yet watched can be recommended to him.
![Capture](https://github.com/aryan-mundra/movie-recommender-django/assets/144268029/657d0226-6014-4f6d-9abd-d72cff65a211)

Recommendations -
![Capture](https://github.com/aryan-mundra/movie-recommender-django/assets/144268029/ef97d6e0-2b44-4f9d-947d-90b3dac73783)

Product page-
![Capture](https://github.com/aryan-mundra/movie-recommender-django/assets/144268029/a9a6a159-2513-4509-ab79-e7b31f5f67cb)



# Technologies Used

Web Technologies -
Html , Css , JavaScript , Bootstrap , Django

Machine Learning Libraries -
Numpy , Pandas , Scipy

Database -
SQLite

# Steps to run the code
1) Create and virtual environment
   ```python -m venv env```

2) Activate the virtual environment 
```source env/Scripts/activate```

3) Install required packages to run the project 
```pip install -r requirements.txt ```

4) Create database tables
```python manage.py migrate```

5) Create a super user
   
   ```python manage.py createsuperuser```

If you are using git bash then type 
```winpty python manage.py createsuperuser```

6) Run server
```python manage.py runserver```

7) The application will work now on http://127.0.0.1:8000

