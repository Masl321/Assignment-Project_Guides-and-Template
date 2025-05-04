# Learning Reflection

## 1. How was your experience testing the given Webapp? 

It was similar, but much shorter, than my previous experience doing application tests in a work environment.
The text and markdown style of protocoling seems a bit weird at first but is better to navigate than an excel alternative.
I do wonder how larger projects would work with this style though.

## 2. How did you write or manage your test case? Describe the process.

I wrote it like a report. Only focus on what happened in a detailed but impartial way.
I clicked through the test cases on gitlab as I was writing the tests to make sure my tests capture the actual process
completely. If I noticed something that I think could go wrong in this process I made sure to include a test.
This also kind of lead me to mostly creating Tests that are similar but not the same than the examples.

## 3. Do you recommend any other tools or styles for Test case management. 

At work we use Excel which can be better for coloring and automatic evaluation.
You can also create seperate sheets for different things.
I personally prefer it that way but it's not drastically different.
What also works well with User-side applications like this is to make a testsuite where each test builds on top of the last one.
I. e. after the Sign-Up test having a test for creating the first project where you can then perform the project tests.
That introduces some flow into the tests and cuts some redundancy for the tester, but can introduce some mistakes through sloppyness.

## 4. Which IDE (Visual Code or Atom or else) have you used to edit files?

I used Visual Studio Code.
    
## 5. Did you find any trouble? how did you solve the trouble?

I didn't have any particular issues although the checklist doesn't seem to work as intended because without the plugin you have to edit the checklist manually in markdown mode

## 6. Did you find any trouble using Github? have you used Github before? where?

I use Github pretty much daily for my work as software developer so I didn't have any issue.

## 7. If in the future if you need to automate these test cases, which framework or language will you use? and describe why (Robot Framework, Cypress, Selenium, or any other )

Since Selenium is as far as I know the de facto market leader I would choose that, because not only is it versatile and offers a lot of compatibility out of the box.
But also because as an organization you generally have an easier time finding qualified people for a widely used and supported framework.
It also introduces less risk because whatever Issue you have will not be contained to only you and as such probably be fixed quicker.
Selenium also allows tests to run concurrently cutting the testing time rapidly, 
which is arguably the most important thing about modern testing and why we even automate tests at all. Testing time is usually very short comparatively,
because either the deadline was set way to short for delivery or something happened which delayed it.

## 8. Kindly search the term `Tester` `Automation Tester` glassdoor and LinkedIn or any other job search website. Currently, list the skills and competencies that are most in-demand in software testing

- previous Experience
- Knowledgeable in testing, ideally has some sort of certification
- technical knowledge of application creation
- analytical workstyle
- communicative
- knowledge of whatever environment they are using (Linux, Windows, Docker ...)

## 9. **Let's assume** that if you are going to continue with the career in Software Testing, which technical and soft skills do you need to fill up the blank in your resume?

due to my prior job experience in IT consulting, I think I got most of the points except:

- Certification in testing
- knowledge of some environments

## 10. Write short Learning Reflection and  Free words Do you think that project helped in putting theoretical knowledge into practice? Describe? (is there anything else that you would like to share with us concerning the current study module). e.g. regarding the quality of content and your learning (or) improvement ideas? 

I think this course and this project has helped me structure and categorize previously acquired knowledge to overall deepend my understanding.
While I have previously been tasked with testing applications before client delivery I was pretty much given a carte blanche on how I would do this.
This lead to me just using the simplest approach without really thinking about the larger picture. I think this allows me to standardize my approach further
and maybe even change the way my project does testing in the future.
I liked the structure of the course but I personally didn't enjoy having to watch all these shortform videos linked together like that on Percipio platform.#
I personally would like a couple of longterm videos more, because on some topics the length of the videos was a bit detrimental to the content and I had to look up the information
from other sources. Its also kind of confusing not having all the course content on canvas.
I did like the overall way the course was being conducted however and I feeled like the quizzes were all fair.
It would be interesting to have like an assignment about the whitebox testing methods, but I guess that might be out of scope...
