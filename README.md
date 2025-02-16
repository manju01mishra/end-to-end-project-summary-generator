# Summary_Generator
Used Flask API to integrate,python script with a web application. Deployment is done on Heroku cloud platform. Following is the link to the web application:    https://textsumgen.herokuapp.com/

# Requirements:
You must have following python libararies installed on your machine. Please refer to requirements.txt file for details.

1.Flask (for creating web application).

2.NLTK (for natural language processing).

3.Networkx (for using graph based algorithms).

---

# Project structure:
The projects has following major parts:

1.app.py : Contains Flask APIs that receive inputs through GUI, calls the main python script for processing and returns the output.

2.summarizer.py : Contains python code to generate text summary from original text.

3.templates : Contains HTML files that allow user to interact with the application.

---

# Running the project:
1.Open Ananconda command prompt and move to your project home directory.

2.Run app.py using below command to start Flask API python app.py.

3.Navigate to the localhost to view the application home page. Localhost: http://127.0.0.1:5000/

4.Enter the text to summarize in the texbox and hit Summarize button.

5.If everything goes well, you should be able to see the summarized version of the text on the results page.

