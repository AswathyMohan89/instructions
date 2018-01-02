# instructions

### Python

mac : Goto https://www.python.org/downloads/ and download latest version

windows : Goto https://www.python.org/downloads/windows/ and download latest version

### conda
mac : Goto https://conda.io/docs/user-guide/install/macos.html follow directions
windows : Goto https://conda.io/docs/user-guide/install/windows.html follow directions
#### Remember to add to PATH variable during installiation
To verify goto (Terminal/GitBash) and type `conda -V` or `conda list`.

#### Create conda environment

`conda create -n PythonData python=3.6 anaconda` 

`source activate PythonData`

`python --version`
#### Create first program
`cd Dekstop` will change to the desktop directory

`mkdir PythonStuff` will make a new directory/folder on the desktop.

`cd PythonStuff` will move to the newly created folder

`open .` on a Mac or `explorer .` in PC will open the current folder

`touch first_file.py` will create a file

`touch second_file.py` will create a second file

`start <filename>` will open <filename>.py in editor
  
`ls` will show what in the current directory

`cd ..` will move us up a director back to Desktop`

#### Github

`git add -A`

`git commit -m <msg>`

`git pull`
###### If made updates in the pulled repo then do:
`git fetch`

`git reset --hard origin/master`

### Api
1. http://www.omdbapi.com/apikey.aspx -OMDB
2. https://openweathermap.org/appid -OpenWeatherMap
3. https://developer.nytimes.com/signup- NyTimes
4. https://console.developers.google.com/apis- Google Maps
5. https://apps.twitter.com - Twitter

create api keys

#### tweepy

`source activate PythonData`

`pip install tweepy`

https://apps.twitter.com/
create app and create token

#### vader- sentiment analysis

`source activate PythonData`

`pip install vaderSentiment==2.5`
