To Run the Movie Recommendation System project:

Step-1: Install all the libraries mentioned in the requirements.txt.
Step-2: Login and get your API key from https://www.themoviedb.org/ and replace API key in recommend.js file
Step-3: Open your terminal from the project folder and execute the command: >python main.py
Step-4: Open your browser at the following address: http://127.0.0.1:5000/

------------------
Backend directory:
It contains the files of preprocessing the datasets and training of the model.
Also, it contains the pickle file which is used to serialization of the data.
In the main.py file, the cosine similarity is used to generate the reccomendation 
of the movie based on our dataset.

-------------------
Frontend directory:
It contains the javascript file which used for the user interface of the application.

-------------------
Dataset directory:
It contains the processed data through which the model is trained.
