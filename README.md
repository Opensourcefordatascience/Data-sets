
Here you can find all data sets that are used is examples at <b>Pythonfordatascience.org</b>.

These data sets are open to the public and can be downloaded and used by anyone. The sources of each data set will be inlcuded in this README file.

To download all files, click the <i>Clone or download</i> drop down arrow and select "Download ZIP". This will download all the data sets used. Another option is to click on the file that you are interested in and click the "Raw" button which will open the file the browser. From here, the URL link can be used in the pandas.read_csv() method and it will import the dataset.


<b>Data sets (in no particular order)</b><br />
The <b>Energy Level.csv</b> data set is a simulated data set that was created to be used in an independent t-test and compared two groups, Group A and Group B, on some outcome measure. The values range 1-10 and can represent anything that fits within that scale. It was created using the following Python code:

np.random.seed(12345678)

df = pd.DataFrame(np.random.randint(10, size= (100, 2)),
                  columns= ['Group A', 'Group B'])

df.to_csv("Energy Level.csv", index= False)

The <b>automotive_data.csv</b> file was downloaded from Kaggle.com from the user Ramakrishnan Srinivasan; the link to the full page is here: https://www.kaggle.com/toramky/automobile-dataset

The <b>responses.csv</b> file was downloaded from Kaggle.com from the user Miroslav Sabo; the link to the full page is here: https://www.kaggle.com/miroslavsabo/young-people-survey. The "Participant Number" column is not part of the original data set. This was added to show examples on how to merge.

The <b>responses_state.csv</b> file is a simulated file (not real data) to be paired with the responses.csv data in the merging examples.

<b>admission.csv</b> file is from the logistic regression example created by UCLA for their walk through of how to conduct logistic 
regression using Stata. The original data link is here: https://stats.idre.ucla.edu/stat/stata/dae/binary.dta

<b>blood_pressure.csv</b> is an example data set that is included in Stata. This file was exported from within Stata to be used within
Python.

<b>difficile.csv</b> is a made up data set that was created to be used in an example.

<b>fairpoor.csv</b> is a made up data set that was created to be used in an eample.
