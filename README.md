# SC22-BatchC-Molten-Cores - GARY 
![GARY](https://media.discordapp.net/attachments/998386145283035177/1003673790045224990/2022-07-22_12-40.jpg?width=586&height=554)
## Project Idea
GARY - Comedy AI that generates jokes for the user based off a given prompt. Featuring 3 different models: Dad jokes, Patton Oswalt, and "Groot model". The prompts are run through the selected model, censored using a list of various curse words, and finally outputed onto the website.

## nlp_writer_scaffold
A scaffold for deploying dockerized flask applications showing student natural language processing projects using aitextgen and pytorch.

## File Structure
The files/directories which you will need to edit are bolded, and the files you may need to edit are italicized. DO NOT TOUCH OTHER FILES.

- Dockerfile
- config.py
- entrypoint.sh
- host_config
- nginx_host
- test.text
- app/
  - main.py
  - utils.py
  - test.text
  - requirements.txt
  - templates/
    - Write-your-story-with-AI.html
    - writer_home.html
    - index.html
  - static/
    - favicon.ico
    - css/
      - styles.css
    - img/
    - js/
      - scripts.js
  - pycache/
    - main.cpython-38.pyc
    - main.cpython-39.pyc
    - utils.cpython-38.pyc

## main.py
Contains the main flask app itself.

## static/
Contains the static images, CSS, & JS files used by the flask app for the webpage.  Place all your images used for your website in static/images/. 

## templates/
Contains the HTML pages used for the webpage. Edit these to fit your project. writer_home.html is the landing page, Write-your-story-with-AI.html is the result page.

## Files used for deployment
Dockerfile uwsgi.ini wsgi.py nlp Do not touch these files.
