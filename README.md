# Data Analysis - Probability and Distributions
### Topics:
- Discrete Random Variables, Probability Mass Functions, Expectations.

### Grading:
- Points are listed next to each question and should total 25 points overall.
- Grading will be based on the content of the data analysis as well as the overall appearance of the document.
- Late assignments will not be graded.

### Instructions:
- Clearly label and type answers to the questions on the proceeding pages in Word, Google Docs, or other word processing software.
- Insert diagrams or plots as a picture in an appropriate location.
- Math Formulas need to be typed with Math Type, LaTeX, or clearly using key board symbols such as +, -. *, /, sqrt() and ^
- Submit assignment to the Gradescope link as a PDF. Indicate the pages to the individual questions and also verify the correct document has been uploaded. Failing to follow this direction may result in point deductions.
  - If you are unable to answer any questions before the submission deadline, please still match the question location to the correct page when submitting in Gradescope.

### Allowances:
- You may use any resources listed or posted on the Canvas page for the course.
- You are encouraged to discuss the problems with other students, the instructor and TAs, however, all work must be your own words. Duplicate wording will be considered plagiarism.

## Part 1 (6 points)
For each random variable, state whether the random variable should be modeled with a Binomial distribution or a Poisson distribution. Explain your reasoning. State the parameter values that describe the distribution and give the probability mass function.

### Random Variable 1 (3 points)
A cabinet manufacturer tests the quality of its drawers by how easily the drawers slide open and shut. From prior studies, the manufacturer determined that 3% of drawers fail the easy slide test. A manufacturer samples 20 drawers from a batch. Assuming the chance of failure is independent between drawers, what type of distribution could be used to model the number of failed drawers from the sample of 20? Hint: the event of interest here is a drawer failing.

### Random Variable 2 (3 points)
The warranty for a particular model of car is 2 years, during which time there is no limit to the number of warranty claims per car.  Historically, the average number of claims per car during the period is 0.65 claims. What type of distribution could be used to model the number of warranty claims per car?

## Part 2: (11 points)
Wheel of Fortune is a popular game show on Television. Contestants spin a wheel and try to guess a correct letter from a word puzzle. If they guess correctly, they earn the dollar amount from the wheel. If they spin “bankrupt” or “lose a turn” they get nothing and can’t play. To the right is an example of the wheel.  Watch this video to see an example of someone spinning the wheel. https://www.youtube.com/watch?v=_Pv33JWBdY8

![image](https://user-images.githubusercontent.com/25465133/164578481-354a6c20-26a5-4810-84c0-fe767e904936.png)

The outcome of a spin on the wheel is a discrete random variable. Consider X the dollar amount spun on the wheel, where Bankrupt and Lose a Turn = $0, and Free Play = $500. There are 24 wedges on the wheel.

![image](https://user-images.githubusercontent.com/25465133/164578600-6f674c90-af9e-496d-94ce-7c6e0cad1385.png)

The following table provides the probability mass function for X. Round values to 3 decimal places.

x | $0 | $300 | $350 | $400 | $450 | $500 | $550 | $600 | $700 | $800 | $900 | $5000
---|---|---|---|---|---|---|---|---|---|---|---|---
Count | 2 | 5 | 1 | 2 | 1 | 3 | 1 | 3 | 1 | 2 | 2 | 1
P(x) | 0.083 | 0.208 | 0.042 | 0.083 | 0.042 | 0.125 | 0.042 | 0.125 | 0.042 | 0.083 | 0.083 | 0.042

1. (1 point) What is the most likely dollar amount?
2. (1 point) How likely is it to spin Lose a turn or Bankrupt?
3. (3 points) What is the average dollar amount? Show work!
4. (3 points) Suppose a contestant spins the wheel three times, how likely is it they spin $0 each time? Show work!
5. (3 points) Suppose a contestant spins the wheel three times, how likely is it they spin $0 at least one time? Show work!

## Part 3: (6 points)
The PMF in Part 2 is based on probability theory. Do these probabilities stand up when a contestant actually spins the wheel?  Go back to the Data Analysis #3 instructions page on Canvas, download the R script titled: Wheel_of_Fortune_Spin_Script.R  , open the file it will automatically open in R. You need R software on the computer to open the script window.  Follow the instructions in the code then answer the following:  

1. (1 point) What value did you spin?
2. (1 point) What is the average of the 1000 simulated spins? How different is this from part 2c?
3. (1 point) Paste the probability mass function and the plot of the probability mass function from R.
4. (1 point) How different are the simulated probabilities to the theoretical probabilities in part 2?
5. (1 point) Based on the plot is the most likely outcome the same as it is in part 2a?
6. (1 point) In general, what action will make the simulated values more like the theoretical ones?

## Gradescope Page Matching (2 points)
When you upload your PDF file to Gradescope, you will need to match each question on this assignment to the correct pages. Video instructions for doing this are available in the Start Here module on Canvas on the page “Submitting Assignments in Gradescope”. Failure to follow these instructions will result in a 2-point deduction on your assignment grade. Match this page to outline item “Gradescope Page Matching”.
