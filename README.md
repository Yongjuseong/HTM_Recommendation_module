# HTM_Recommendation_module

This is a recommendation module that is used in HTM("Home Training Manager") 

In HTM, we recommend exercise videos to users based on the rating of each exercise videos and the user's data.

So, we convert our DB to csv files in HTM_data folder(Actually, the most of data is fictional to test the model).

We use the "Latent factor collaborative filtering" by using matrix factorization to find the latent.

Matrix factorization: Dimension Reduction- Singular Value DecompositIon(SVD, and we use it from Scipy library)


Version info----
Python 3.8
Sklearn
Scipy
Numpy
Pandas
Matplotlib
Seaborn
Colab(test the model in this environment)


<2020/12/16>
Usage-In actual use, you need to install the python library on the server.

<Required Library>
sklearn
Scipy
matplotlib
Seaborn
Panda
numpy


<In case of data loading part error>
Loading csv files should be fixed in case of errors.

It is now defined as follows based on the standard module.

df_ratings = pd.read_csv ('./ HTM_data / video_ratings.csv') # Read user-exercise video data, ratings.csv
df_videos = pd.read_csv ('./ HTM_data / exercise_videos.csv') # read video (exercise video) .csv


When an error occurs
Based on the server source file that launches the entire app, you need to modify the address to be relative or absolute at all.

