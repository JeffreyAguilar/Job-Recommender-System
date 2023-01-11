# Job-Recommender-System

In the busy lives of college students looking to become working professionals in industry, looking for a good job in the vast sea of vacancies can be very time consuming.  There are many job applications and finding websites such as Glassdoor, Linkedin, and Indeed where you have to manually input information to find the desired job through their search engines that are already typed into your resume.  So why isn’t there a search tool where you can easily find jobs with the best match based on your resume? Well with our Job Finder Application, now there is.  

Our job recommendation system is a content based system which takes in application (specifically from Glassdoor jobs data for open Data Science positions).  The main effect of the application is that it takes in job descriptions from this dataset and compares them against the resume of a person as a user query through TFIDF , while utilizing the SKLearn algorithms of Cosine Similarity and K Nearest Neighbor Search aid in finding similarity scores for the top 20 results.  
PDFPY2 takes in Resumes and CSV Reader takes in the Jobs Dataset and Descriptions where on the colab notebook, the resumes undergo preProcessing, tokenizing, and lemmatizing.  They are then vectorized and prepared to be put into the Cosine Similarity and KNN Models where they are used to be compared against one another, returning arrays of score based on similarity.  The top 20 jobs for each one of these methods is printed out.  

