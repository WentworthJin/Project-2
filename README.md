# Project-2

## Students:
- Liangbo Jin  23078811
- Kebing Zhao  22863702

## Purpose of the Web Application
The purpose of this <b>Web Application</b> is to provide fundentmental concept and small test of the <b>Swift</b> programming 
language, and offer feedback for each test.  

## Context & Assessment mechanism
- For the context, we created several tutorial pages for users ( login / non login) to visit and learn. In addition, a user cannot enter the 'Test' page unless he is registered, what's more, a registered user cannot view his profile page until he finished one test.
- The admin account is used for adding and deleting user's data, including their account and test's result. Only the admin user can visit the admin page, and perform editing.
- We provide 10 questions that related to the tutorial materials. For each question, if user gives the right answer, the temperory <b>int Mark</b> will add 10 mark. Otherwise, if user gives the wrong answer, the temperory <b>string Feedback</b> will add the feedback for the current question.

## Architecture of the Web Application

## How to Launch the Application
1. Open the terminal under the file directorym, and run the following commands in terminal
2. Using the <b>pip</b> to install all the packages in the '<b>requirements.txt</b>
<pre>pip install -r requirements.txt</pre>
3. Run the Application
<pre> flask run </pre>


## How to run Unit Test
1. Run the command  <b>flask run</b>, and keep the local server on.
2. Run the python file  '<b>testBot.py</b>', and wait for the test finish.
3. Once you see the test's status: Test # finished, the tests are finished. ( As show below)
<pre>
Process finished with exit code 0
PASSED                                        [ 50%]Register Here ! 
Test1 finished!

PASSED                                        [100%]Congratulation!!! 
Test2 finished!
</pre>

## Commit log
The log file is named as  '<b> log.txt</b>', and all commit logs are stored inside the file.