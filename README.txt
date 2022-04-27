___________.__          __________.__                       __________                    .___
\__    ___/|  |__   ____\______   \  |  __ __   ____   _____\______   \_____    ____    __| _/
  |    |   |  |  \_/ __ \|    |  _/  | |  |  \_/ __ \ /  ___/|    |  _/\__  \  /    \  / __ | 
  |    |   |   Y  \  ___/|    |   \  |_|  |  /\  ___/ \___ \ |    |   \ / __ \|   |  \/ /_/ | 
  |____|   |___|  /\___  >______  /____/____/  \___  >____  >|______  /(____  /___|  /\____ | 
                \/     \/       \/                 \/     \/        \/      \/     \/      \/ 
                
----------------------------------Description--------------------------------

BIO also known as the Bitcoin Information Obtainer website returns bitcoin
information based on an inputted bitcoin hash through a website interface

---------------------------------Instructions--------------------------------

Instructions for testing website locally with Python:
Im currently using version 3.9.5 of Python to run this local server but 
I believe all versions after 3.7 should work fine

For Windows Users:

1.Download BIO.html and save it to your computer

2.Open up cmd and type in the following command replacing DIRECTORY with the
directory to the folder containing BIO.html

	python -m http.server 8000 -d "DIRECTORY"

	(Note Im using 8000 as my port but this can be changed if you desired)

3.Open up a broswers and type into the url bar http://localhost:8000/

4.Select the file named BIO.html and the website will open

-----------------------------------------------------------------------------
