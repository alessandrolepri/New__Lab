# News Labs – Junior Software Engineer

## Dataset

 In this exercise, we provide you with a subset of this data collected during Direct Assessment evaluation. Each row shows the 2 translations and the original text along with the score that an evaluator has given. Each sentence has been scored multiple times by different evaluators.

File1:

* bulgarian-direct-assessment.csv

Each row is made up of:

* sentence_id: a unique id for each sentence(the same sentence will have been evaluated multiple times)
* evaluator_id: a unique id for each evaluator(the same evaluator will have evaluated multiple sentences)
* score: the score the evaluator gave each machine_translated sentence
* human_translation: the sentence as translated by a human
* machine_translation: the sentence as translated by a machine
* original: the original sentence in English

## Exercise

For this exercise, we’d like to ask you to write code to read in the data file and generate outputs for the exercises below.
For each exercise, starting with the original CSV file:
* Generate a JSON file that contains the average score given by each evaluator.
* Generate a JSON file that contains the average score for each sentence and the highest and lowest scoring sentence.

## How to runs

* Clone the repo on your local
* install all dependency ```npm i```
* get the data from terminal typing ```node index.js``` to get all the result to the terminal page

## Approach and Solution

* From the zip file I have exported the csv file and integrated to the repo as 'bulgarian-direct-assesment.csv'

* From the Terminal I have ran ```csvtojson bulgarian-direct-assessment.csv > index.js``` to create an array of object, then I have modified then syntax to the csv file to concatenate all the word such as 'sentence_id', 'evaluator_id', 'human_translation' and 'machine_translation' in order to not get any undefined return

* I have decided to use 'reduce()' function based on the task of the exercise as I have to return all the score up as single number.
It will help me to cycle through each number in the array and return only the accumulator needed to calculate the average by dividing by
