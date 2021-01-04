# movieRecommdationSystem
There are 3 python notebooks 1 each for demographic,content-based and collaborative filtering ,the dataset are present in the parent folder.Please change the data path if you are running in your local machine.
In colab you can directly access data using this link by mounting the google drive as shown in all the notebook.(Skip this line if running on local machine and change the filepaths where data is read into the DataFrame)
https://drive.google.com/drive/folders/1ROYr4OCIBkqjbPwKlQi9Q7SJD__3uUzo?usp=sharing
https://drive.google.com/drive/folders/1R6l-74nq7CKpgK0j-iyEiYF8bZnJN_9x?usp=sharing
For TmDb movies dataset and movieLens user rating datasets respectively
1)For demographic filtering no input needs to be given as the recommendations are general based on popularity,ratings,director,actor etc. just run all the cells and check the recommendations
2)For content based filtering you need to input the number of movies rated,corresponding movie names and ratings in the input prompt that shows at the end of the notebook.Please check out the exact movie names ‘The’,case of initials etc.A cell has been provided to check the rowId of the movie if that comes out to be ‘-1’  your movie is invalid.Moreover,the prompt also flags an error and asks for the to be fed again.
3)For collaborative filtering change the userId(‘id’) which has been set to 348 to get recommendations for other users.
