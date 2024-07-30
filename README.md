# Bachelor-Arbeit-Exp
Here are all the files with the different experiences we've tried.

List of the two blocks of experiences we did to show to what extent clickbait content is given greater prominence in recommandation algorithm. This list is in the order of our work: 

Content-based filtering:
- analysis
- tf-idf
- word2vec
- sentence transformer
- content based filtering

In order to try successfully our experience, you have to run the files tf-idf, word2vec and sentence transformer first, because they are going to create new files that we are going to need for the next step. After that, you just have to run the content based filtering file, being sure that the required files have been successfully created, and that's it! 

Note: it is possible that you get an error while running the sentence transformer file. Restarting the kernel should correct this error. 

Collaborative filtering:
- create profils
- collab filtering random user
- collab filtering 50-50 user
- collab filtering 55-45 user

Please do not execute the "create profils" file. We already posted on GitHub the required csv files to do the collaborative filtering. The collab filtering random user file uses the csv file: user_interactions_random. The collab filtering 50-50 user uses the csv file: user_interactions_50_50.csv. And the collab filtering 50-50 user uses the csv file: user_interactions_bias_55_45.csv. There is no order to this part of the experience, it is just important to note that each “collab filtering“ file performs the same experiences but using different csv files.

You'll find a detailed explanation of our experiments, an analysis of the results and an introduction to why we chose these demonstrations in chapter four of our work, starting on page 29.
