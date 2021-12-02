# Auto-suggestion-and-Auto-correction-in-Epics </br>
## Environment setup
Create a new virtual environment and install all the dependencies mentioned in
requirements.txt. 
## Data Source and Extraction
1. Downloaded raw data from the Internet Sacred Text Archive and stored
them in the mahabharata-english folder. Processed this raw data to create
the datasets used in insights and our model. 
• The processed datasets are stored in the data/ folder and the script used
to process the raw data is Data Collection/read_mahabharata.ipynb.
Execution
• Simply unzip the zip file and run each of the notebooks present in the
Auto-Complete folder and Auto-Suggestion folder respectively
• The following are the scripts for each of the tasks:
– Insights:
∗ Data Analysis and Auto-Completion words Dumping -> AutoComplete.ipynb
∗ Neural-Network Model Auto-Suggestion -> lstm.ipynb(Already
trained model is present with name as mymodel.h5.Load it directly
in the ipynb file)
∗ Probabilistic Model Auto-Suggestion -> Auto_Suggest.ipynb
Other Links:
• Project Report
• Project Presentation Slides
• Codebase
