## Introduction 
This is a collaborative project with other students at the University of Melbourne using the [Hollywood Stock Exchange](https://www.hsx.com/) database. My role in this project was writing a program that calculates the cost basis for each trade by wrangling the HSX data using python and the pandas library. The trickiest part of this task is controlling for complexities. Specifically, the cost basis calculation depends on factors such as trade type (Long or Short), and the remaining quantity held in each position. The big reason why data calculation has to be done in python, instead of SQL this time, is because it has to refer to previous rows for very specific conditions. Therefore, I also had to control for cases of the first row or first trade action calculations using for loops with if statements.

<img width="683" alt="LiveDashBoard" src="https://user-images.githubusercontent.com/94946621/205501174-3908cdf7-1d39-494d-81e5-4d4bf258a08c.PNG">

## Statement of originality 
Aside from the dataset, which was provided by the University of Melbourne, I hereby declare that the work presented in this project is an outcome of my independene and original work. The project is free from any plagiarism and has not been submitted elsewhere for publication.
