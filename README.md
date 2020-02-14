# News Labs – Junior Software Engineer – Coding Exercise

## Dataset

 In this exercise, we provide you with a subset of this data collected during Direct Assessment evaluation. Each row shows the 2 translations and the original text along with the score that an evaluator has given. Each sentence has been scored multiple times by different evaluators.

File1:
* bulgarian-direct-assessment.csv

Each row is made up of:
* sentenceid:auniqueidforeachsentence(thesamesentencewillhave
been evaluated multiple times)
* evaluatorid:auniqueidforeachevaluator(thesameevaluatorwillhave
evaluated multiple sentences)
* score:thescoretheevaluatorgaveeachmachinetranslatedsentence
* humantranslation:thesentenceastranslatedbyahuman
* machinetranslation:thesentenceastranslatedbyamachine
* original:theoriginalsentenceinEnglish

## Exercise

For this exercise, we’d like to ask you to write code to read in the data file and generate outputs for the exercises below.
For each exercise, starting with the original CSV file:
* GenerateaJSONfilethatcontainstheaveragescoregivenbyeach
evaluator.
* GenerateaJSONfilethatcontainstheaveragescoreforeachsentence
and the highest and lowest scoring sentence.

## How to runs

* Clone the repo on your local
* install all dependency 'npm i'
* get the data from terminal typing 'node index.js' to get all the result to the terminal page

## Solution

* From the zip file I have exported the csv file and integrated to the repo as 'bulgarian-direct-assesment.csv'

* From the Terminal I have ran 'csvtojson bulgarian-direct-assessment.csv > index.js
' to create an array of object and modified to syntax to the csv file to concatenate all the word
