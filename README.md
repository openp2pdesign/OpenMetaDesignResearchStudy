![app/public/logo/OMD_logo_large.svg](OMD_logo_large.png)

# Research Study
The [LimeSurvey](https://www.limesurvey.org/) questionnaire and [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/) notebooks for testing OpenMetaDesign, a platform for the collaborative design and discussion of collaborative design processes.

# Questionnaire
Import the ```questionnaire/limesurvey_survey_831363.lss``` or ```questionnaire/limesurvey_survey_831363.txt``` into LimeSurvey.

Export the results to ```csv/results.csv``` with just the question codes and not the full questions. The Notebooks are configured to read just the question codes as the columns titles.

Export the coding results from MAXQDA into ```csv/maxqda.csv```.

You can create the ```csv/outcomes.csv``` files with [git-quick-stats](https://github.com/arzzen/git-quick-stats) with: ```git quick-stats``` choosing ```9) Git commits per date```.

# Notebooks
Clone the repo:

```
git clone https://github.com/openp2pdesign/OpenMetaDesignResearchStudy.git
```

Enter into the project

```
cd OpenMetaDesignResearchStudy
```

Create a Python Virtual Environment:

```
virtualenv env
```

Launch the Python Virtual Environment:

```
source env/bin/activate
```

Install dependencies:

```
pip install -r requirements.txt
```

Launch Jupyter Lab:

```
jupyter lab
```

Open a browser to [http://localhost:8888/lab](http://localhost:8888/lab)

At the end, close the Python Virtual Environment:

```
deactivate
```

# License
[MIT License](https://choosealicense.com/licenses/mit/)
