# CSCE-771-Final_Project

To run the project go inside the code directory and run the ex_text_summarizer jupyter notebook.
Be sure to include the text file you want to summarize in the code directory, with the summary provided in the dataset (data directory).
To Select thenews article in the dataset Select the data directory -> Select the BBC News Summary directory -> Select the News Articles Directory -> Select any of the directories -> copy any of the file (Remember the filename) into the root directory (code directory).
To Select thenews article in the dataset Select the data directory -> Select the BBC News Summary directory -> Select the Summaries Directory -> Select any of the directories -> copy any of the file after renaming it to (name_summary.txt, for instance if the file is 001.txt, rename it to 001_summary.txt) into the root directory (code directory).
You can also use any text file that you provide by putting it into the code directory and renaming it to 001.txt for example. It should contain 3 characters before the .txt extension and if you provide the summary file make sure to rename it to 001_summary.txt if you are using 001.txt as your original document you want to summarize.
To check the similarity between a summary provided and the summary generated through the project use the similarity_checker jupyter notebook, and before you do so please make sure to run the file through the ex_text_summarizer jupyter notebook so that it gets added to the summaries.csv file. Note that the row number in the csv file containing a summary corresponds to the similarity_checker's output. For example if the output says Similarity for doc 1, then it has calculated the similarity of the summaries present in the first row of the csv file.

The project report can be found under the report directory
