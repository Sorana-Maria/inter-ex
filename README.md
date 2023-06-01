# inter-ex
## Process

I will walk you through what I did and some insights I had.

### Part 1

First, I wanted to get a better understanding of the task so I used Google and ChatGpt.

I proceeded to learn more about **APIs, Matplotlib** and installed the necessary modules.

I wrote the code and *(hurray!)* the plot was good.

### Part 2

The following step was to move it to GitHub and learn about CI/CD. The CI/CD I found to be quite difficult to put into practice. I created a repository to just practice and try more on it.

I tried some workflows for what I had *(CodeQL, Pylint, Python testing with Conda)* and got errors of which I did not see the functionality; *for example, the name of the variable not corresponding to snake as it was only one letter as in the case of “x” and “y” when plotting.*

After that, I found **Python Application** which I think was a better workflow to use and started running tests on the code.

I used **unittest** and it worked in VisualStudio; however, in GitHub, I saw an error related to pytest, decided to try with that, but still got the same error. I stuck to unittest in the end as I am a bit more familiar with it.


### Part 3

I proceeded to create a new repository to have it more *clean and structured*; *divided the code into its functions* and *committed them one by one* in a secondary branch. After that, I opened the code again and ran it. In the end, pushing it to the main branch *(which looking back to, I probably should have done one by one as well)*. 

## Overview

Now, I saw the Python Application was still showing that error. *CI/CD are still new concepts to me*.

*My theoretical understanding* of them so far is that a **CI/CD pipeline is used to ensure that a team can work and make changes to their code in a reliable way.**

The pipeline begins with Continuous Integration (CI), which automatically builds and tests the code changes whenever they are committed. This would allow catching any bugs or errors early in the development cycle, before they can cause more serious issues.

Then, Continuous Deployment (CD) involves automatically deploying the code changes once they have passed all of the tests and quality checks. This would ensure that the software is always up-to-date and running well.

Overall, implementing a CI/CD pipeline aids in improving the software development processes by reducing errors and increasing productivity.

### Brief 

The code and application seemed easy, at some point I was even wondering if I am doing something wrong because of that. The harder part came when encountering the CI/CD pipeline, but **I am confident that with more practice I will get the hang of it** as well.

