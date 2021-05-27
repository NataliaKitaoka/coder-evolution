# coder-evolution
<p>This project was made to complete the Data Scientis course at Udacity. And it aims to observe the coder (someone who codes) evolution profile through the years considering their formal degree.</p>

# 1. Installation
<p>For this project were not used any other library besides that which are already in Anaconda Distribution. <br>
The Python version was updated to Python 3.8.5 here.</p>

# 2. Project Motivation
<p>This project used all databases from Stack Overflow Annual Survey from 2017 to 2020. After looking to these databases some questions emerged and they are listed bellow. The main purpose was to evaluate the necessity of having a formal degree in Computer Science or any other related undergrad degree to be a developer or a professional who codes in his daily activities.</p> 

1. How important is a formal education, such as a university degree in computer science, to your career?
2. Is there any bias in the above opinion depending on their major undergrad?
3. What is the proportion between these two type of professionals along the years?
4. Depending on your degree, there is difference in salary or compensation if you work coding? How does it is indicated along the time?

# 3. File Descriptions
<p>There is just one Jupyter notebook here titled 'coder-evolution'. In this notebook there is the code used to analyse the datas from StackOverflow, so there are data visualization and data processing in it aiming to answer the questions listed above.</p>

<p>Each question and data processing by year were denoted by a markdown cell or by comments.</p>

# 4. How To Interact With Your Project 
<p>For each question were used the apropriate variables to answer the questions. Basically the variables were the same for datasets from 2020 and 2019, but 2018 and 2017 had different variables, so for some questions like the third and the forth were used some equivalencies of variable names and its values to achive same answers from different datasets.</p>

<p>It is important to point that were considered a person who codes is someone who is working professionaly and is a software developer or someone that codes somehow as routine even if it works belongs to management skills too. For exaple: data scientists, full-stack,back-end, front-end, data base analyst... even a CEO with code activities at work was considered. And this assumption was done because the type of professions was only described in 2018, in the others datasets it was only said if the person codes or not. It was assumed that even if coding is not the mainly activitie for some of the professions considered, they could at least opine about the importance of having a formal degree or not to get access into the "coding market". The others were considered as people who doesn't whor coding.</p>

<p>The other assumption is that a person who had a formal degree in Computer Science is someone who had its major undergradute in computer science, information system, web development, computer engineering or any other course that teaches about programming deeply. The others were considered as non computer scientist, even if the person answered with Nan, because in that case probaly for her it wasn't necessry a bachelor or any other formal degree to get a job.</p>

<p>About the salary, there were same difficulties as explained above for professions. The datasets from 2020 and 2019 used annualy compensation to measure how much each respondent earned in his job, and were used the variable of annualy converted salaries to U$ dollars. In 2017 and 2018 the variable was 'Salary' and in 2017 was only considered the people who earned in U$ dollar, because there wasn't the variable 'converted sallary'. </p>
	
# 5. Results
<p>A blogpost on Medium with my main results can be read here: <br>
[Do you need Computer Science formal degree to become an employed coder?]
(https://natalia-ayumi-moura.medium.com/do-you-need-computer-science-formal-degree-to-become-an-employed-coder-1e847304e830)</p>

<p>I hope you like it!</p>

# 4. Licensing, Authors, Acknowledgments  
<p>I would like to thank to Stack Overflow for providing all of this important datasets about dev community and also for helping me answering all of the "How to..." questions. All the data sets can be donwloaded [here]
(https://insights.stackoverflow.com/survey).</p>
