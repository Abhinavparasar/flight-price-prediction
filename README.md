# ABSTRACT
Air travel has evolved into a popular, necessary, and quick mode of
transportation thanks to the ever-increasing interconnectedness of air routes
around the globe. For airlines, predicting prices is a crucial yet difficult
issue because prices are always fluctuating and are known to depend on
a wide range of factors. With extensive research in the domain, it has
been found that an estimation flight costs at a given time can be obtained
within seconds utilising machine learning, artificial intelligence, and deep
learning approaches. In this study, we employ a machine learning regres-
sion approach to forecast travel costs by using simple information such as
the airline name, source, destination, number of stops, and The outcomes
demonstrate that the Random Forest Regression Model delivers very ex-
cellent outcomes. Basic departure and arrival times.The outcomes demon-
strate that the Random Forest Regression Model delivers very excellent
outcomes.


## Steps to run Flight Fare App - on Windows

* Prerequisites: [Python 3.9](https://www.python.org/downloads/) (ensure Python is added to [PATH](https://medium.com/co-learning-lounge/how-to-download-install-python-on-windows-2021-44a707994013)) + [Git](https://git-scm.com/downloads) Client 
* Open GIT CMD >> navigate to working directory >> Clone this Github Repo (or download project files from GitHub directly)

      git clone https://github.com/Abhinavparasar/flight-price-prediction.git  
* Open Windows Powershell >> navigate to new working directory (cloned repo folder)
* Run Project in Flask (Using PIP + Virtualenv)
 
        pip install virtualenv                  # install virtual environment        
        python virtualenv ENV                   # create virtual environment by the name ENV
        ENV\Scripts\activate                    # activate ENV
        pip install -r .\requirements.txt       # install project dependencies
        python app.py                           # run the project
        deactivate                              # close virtual environment once done
  

### Steps to run Flight Fare App - on Mac

* Prerequisites: [Python 3.9](https://www.python.org/downloads/)
* Open Terminal >> navigate to working directory >> Clone this Github Repo (or download project files from GitHub directly)

        git clone https://github.com/Abhinavparasar/flight-price-prediction.git  
* Navigate to project working directory (cloned repo folder)
* Run Project in Flask (Using PIP + Virtualenv)

        pip install virtualenv                  # install virtual environment
        virtualenv ENV                          # create virtual environment by the name ENV
        source ENV/bin/activate                 # activate ENV
        pip install -r requirements.txt         # install project dependencies
        python app.py                           # run the project
        deactivate                              # close virtual environment once done
        

