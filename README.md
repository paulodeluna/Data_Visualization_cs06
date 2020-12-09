# Data_Visualization_cs06

You can play with the data by uploading this repo into a Google Colaboratory Notebook. 
All you have to do is upload the data into Colab using panda and run all cells. 

Step1
instead of :
data = pd.read_csv("spotify_data1.csv")

you should say:
data = pd.read_csv("https://raw.githubusercontent.com/paulodeluna/Data_Visualization_cs06/main/spotify_data1.csv")

Step2
get rid of:

              from google.colab import files
              import csv

              uploaded = files.upload()

Step3:
On the drop down menu select only Danceability or Artists; you can select songs but you won't see anything interesting. 

Step4:
Click on Runtime/Run All or simply press Command/Ctrl + F9

