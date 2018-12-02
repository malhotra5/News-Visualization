# News-Visualization
An efficient way to visual news. You can type a poular news topic, and the website will get most recent and poplular news reports. It will display it in a network fashion. All related news reports are liked together with a line, like nodes and axons of a neural network. 
## Getting Started
The project requires many modules, that can easily downloaded for Python3. There are no additional installations for the frontend made using HTML, CSS and p5js (javascript for graphics).   
### Prerequisites 
NlTK (symbolic and statistical natural language processing)
Flask (micro web framework in Python)
Flask-cors (Cross Origin Resource Sharing)
Newsapi (search worldwide news articles and headlines)
Newspaper3K (library for extracting & curating articles)
Pdfminer3k (extracting information from PDF documents)
### Installation 
Install using pip

    pip install 'module name'

Module names depend, and can easily be found on the web. 
## Running the website
I used heroku, to run the backend Python. You can run it locally, be editing the Javascript document 'visualize.js'. Search for the string 'http://news-visual.herokuapp.com/?topic=' and change it 'http://0.0.0.0:5000/?topic='. This will let you run the website locally. Now, to connect the backend to the frontend, or in simple terms for beginners, to make the project work run the python script 'api.py'. Then open the website and try it! 
## How it's made
A user types in a topic the want to search up in the search bar. The topic is sent to the backend, where the most recent and popular topics are scraped of the web. NLTK is used to find if there are any similar articles related by theme, topic, etc. The information is sent to the frontend, where all the information is displayed in a network. The panel on the side, has links to the news websites of the articles. 
## Results 
Search Bar for searching news - \
![GitHub Logo](/Images/search.png)

The visualization of news - \
![GitHub Logo](/Images/results.png)
## Built with
* Python3
* p5js
* CSS Bootstrap
* HTML
## Acknowledgments
My hackathon partner
