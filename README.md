# instagram-detection-of-cyberr-bullying-
in this projct we extract comment from the post into a exl file after that we analyze that data using the textblob sentiment analyzer and display that analyze data in graphical form .

1 Clone:

git clone git@github.com:AgiMaulana/Instagram-Comments-Scraper.git
or git clone https://github.com/AgiMaulana/Instagram-Comments-Scraper.git
or download the zip

2 Create Virtual Environment (Recommended)

pip install virtualenv
virtualenv .venv

3 Activate the virtual environment

source .venv/bin/activate

4 Install dependencies

pip install -r requirements.txt

5 Install Chrome Web Driver

wget https://chromedriver.storage.googleapis.com/x.xx/chromedriver_linux64.zip
See the latest Chrome web driver on https://sites.google.com/a/chromium.org/chromedriver/downloads

Extract and move the binary to bin: unzip chromedriver_linux64.zip -d .venv/bin/
Make it executable chmod +x .venv/bin/chromedriver

6 Run

python scraper.py post-url total-load-more-click
Change the URL with your post target.
For example : python scraper.py https://www.instagram.com/p/CBHH2KjI6BW/ 5

7 Deactivate the virtual environment

deactivate
