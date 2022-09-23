# Movies-ETL Challenge

# Deliverable 1: Write an ETL Function to Read Three Data Files (25 points)

In this Deliverable, we wrote a function that reads in the three data files given to us in order to create three separate DataFrames. Below is an image of the code i used to direct to the correct folders in order to do so.

![Deliverable1_test](https://user-images.githubusercontent.com/103979087/191897401-c075ab9f-ce12-42eb-823b-42b4ff76b4ce.png)



### Wiki Movie Data Dataframe:

In this section, I converted the Wikipedia JSON file to a Pandas DF by succesfully navigating to the correct folders to link the files.

![wiki_movies_df](https://user-images.githubusercontent.com/103979087/191896727-c070fc9a-b244-40b3-87ef-a5968aeb7541.png)


### Kaggle Metadata Dataframe:

I then converted the Kaggle metadata file to a Pandas DF as well.

![kaggle_metadata](https://user-images.githubusercontent.com/103979087/191896734-522dec33-5edf-485f-a0a3-3d3670c33c6f.png)


### Ratings Dataframe:

Lastly, I converted the ratings data into a Pandas DF.

![ratings_df](https://user-images.githubusercontent.com/103979087/191896737-9d608515-a378-4ce0-b59e-217e040eb75d.png)



# Deliverable 2: Extract and Transform the Wikipedia Data (30 points)

In this Deliverable, we extracted/transformed the Wiki data to merge it with the Kaggle metadata. We then extracted the IMDb IDs using a regex string and droped duplicates, while using a try-except block to catch errors.

Here we see a cleaned version of the Wiki-Movies DF to show the results of the steps taken in the instructions in the first half. Unlike the one from Deliverable 1, it includes Based On, Starring, Cinematography, Release Date, Count, and so forth.

![wiki_movies_df_del2](https://user-images.githubusercontent.com/103979087/191902393-62f25a49-f464-452c-9e3c-9813755a5474.png)

And here we see the Wiki-Movies DF shown as a whole in a list, which is easier to read.

![wiki_df_list](https://user-images.githubusercontent.com/103979087/191902406-d42a09be-2e56-4452-b798-8c5e9a6c89b0.png)



# Deliverable 3: Extract and Transform the Kaggle Data (30 points)

# Deliverable 4: Create the Movie Database (15 points)


