# Election Audit Challenge

## Overview of Election Audi

### Purpose of this election audit analysis

#### Help the elections commission, who have asked for help to include different calculations. Among these calculations would be the voter turnout for each county, the percentage of votes from each county out of the total count and the county with the highest turnout. This would be done by means of for loops in python accessing the election result file (csv) and writing the results to a txt file, analyzing the calculations that were made in this file.

## Election-Audit Results

### The following python code was used to perform the different calculations requested by the election committee. It should be taken into account for the subsequent analysis in the following bullet points.

(imagen 1)

### * How many votes were cast in this congressional election?

#### The total number of votes counted in the election was 369,711 votes, as can be seen in the following code output. This number was calculated by adding 1 to the total vote count for each row in the csv of the election results, as is evident from the code in the total_votes variable.

(imagen 2)

### * Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

#### As it is evident in the output to the txt document of the code, the number of votes and the percentage of the total votes that each county obtained is the following:

    Jefferson: 10.5% (38,855)

    Denver: 82.8%(306,055)

    Arapahoe: 6.7%(24,801)

#### This was calculated as you can see in the code by adding a vote for each time vote was cast in the specific county (Jefferson, Denver and Arapahoe). Then, this number was divided by the total votes calculated above to obtain the percentage of votes that each county obtained of the total votes.

(imagen 3)

### * Which county had the largest number of votes?

#### The county with the highest number of votes was Denver. This, as can be seen in the code, was calculated by means of an if function to verify that both the number of votes and the percentage of these with respect to the total was the highest.

(imagen 4)

### * Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

#### Como se evidencia en la salida al documento txt del código, el número de votos y el porcentaje del total de votos que obtuvo cada candidato es el siguiente:

    Charles Casper Stockham: 23,0% (85.213)

    Diana De Gette: 73,8% (272.892)

    Raymon Anthony Doane: 3,1% (11.606)

#### Esto se calculó, como puede ver en el código, agregando un voto por cada vez que se emitió un voto por el candidato en específico (Stockham, DeGette y Doane). Luego, este número se dividió por el total de votos calculado anteriormente para obtener el porcentaje de votos que obtuvo cada candidato del total de votos.

(imagen 5)

### * Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

#### The candidate who won was Diana DeGette, with a total of 272,892 votes and a percentage of the total votes of 73.8%. This was calculated, as you can see in the code, with an if function to obtain the candidate with the most votes compared to the other candidates and also the highest percentage.

(imagen 6)


## Election-Audit Summary

### Business proposal to the election commission on how this script can be used—with some modifications—for any election.

#### The electoral commission could use this python code to replicate these calculations in future elections just by making some changes in some aspects and be able to obtain reliable results like the current ones. Well, theoretically it would work in most cases if the same method and format is used to save the electoral data that was made in this period.

### Examples of how this script can be modified to be used for other elections.

#### An example of these changes that would have to be made to the code in order to be able to replicate the execution of results would be the name of the csv files in which the electoral results are saved. For this reason, you would also have to change the column number in which different data is located (for example, name and county) to perform the calculations, in case that any location of data has changed.

#### Another example of the things that would have to be changed in the code to make it work in any election would be the location of these files, because when loading them, their location would have to be taken into account. So the easiest way to replicate these calculations with the same code would be to make the csv of future choices and their location the same as the current one.
