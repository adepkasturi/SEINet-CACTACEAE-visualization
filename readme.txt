SEINet Cactaceae dashboard:
The SEINet Cactaceae dashboard presents a series of interactive visualizations to provide a holistic view of the dataset for North America. 

Getting Started:
These instructions will get you a copy of the project up and running on your local machine for development.

Prerequisites:
For Windows and macOS:
1) Python 3.x should be installed.
   a) To download Python 3.x, visit https://www.python.org/downloads/ and download the latest stable version for windows or macOS.

2) Google Chrome 81.x.x.x
   a) To download Google Chrome 81.x.x.x, visit https://www.google.com/chrome/

3) Install Flask.
	a) Open terminal.
	b) Run $ pip install Flask 

4) Install Pandas
	a) Open terminal
	b) Run $ pip install pandas

5) Install CORS
	a) Open terminal
	b) Run $ pip install flask-cors

6) Install skimage
	a) Open terminal
	b) Run $ pip install scikit-image

7) Install cv2
	a) Open terminal
	b) Run $ pip install opencv-pyt

8) Install numpy
	a) Open terminal
	b) Run $ pip install numpy

Installing:
1) Go to Google drive (https://drive.google.com/drive/u/1/folders/128q0V6S5msdIMM9ySAUQKLADAf1VsTk1) and download the images folder.

2) Add this images folder in the current directory (~/seinet_cactaceae_dashboard).

3) Go to Google drive (https://drive.google.com/drive/u/1/folders/1dZlOQZy-YOmViXPfsqH67-e5qkjAIBPO) and download the mwdbSql1.sqlite file.

4) Add this folder in the api folder in current directory. (~/seinet_cactaceae_dashboard/api).

5) Open terminal and change the directory to seinet_cactaceae_dashboard/api folder
	cd ~/seinet_cactaceae_dashboard/api

6) Run python ./api.py .

7) Open another terminal window and change directory to seinet_cactaceae_dashboard/ folder.
	cd ~/seinet_cactaceae_dashboard

8) Run python -m http.server .

Running the dashboard:
1) Open localhost:8000 in your Google chrome browser.

2) To upload an image, click on browse button.

3) Select any image present in seinet_cactaceae_dashboard/api/images folder. To upload any random image, first add that image in this folder.

Common errors:
1) If the loader keeps on running without displaying charts, verify the following:
	a) Image uploaded is from seinet_cactaceae_dashboard/api/images folder only.
	b) Backend api is up and running.
	c) Check terminal with backend api for errors.
	d) Open console in developes tool in Chrome to check for error.

2) If charts are not appearing on home page:
	a) Check if python server for frontend is up and running.
	b) Check if your internet connection is stable.

3) If you do not see any images or icons:
	a) Download the images folder as mentioned in intallation.

Data preprocessing:
All scripts related to data collection, cleaning, aggregation and preprocessing are available in the data_preprocessing folder.
The output files can also be found here.

Similarity matching:
Code for creating db and feature extraction is available in the similarity_matching folder.


Authors:
1) Dhriti Shah
2) Kasturi Adep
3) Omakar Sandeep Vedak
4) Shafquat Bakhtiyar
5) Shrimangal Sanjay Rewagad

Acknowledgments
http://swbiodiversity.org/seinet/ was used to get all data set.