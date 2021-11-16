# project_cs310f2021

## Deadlines:

- _Project Proposal_: November 19th by 11:30am
- _Project Progress_: December 8th by 3pm
- _Final Submission_: December 15th, by midnight

## Table of Contents

- [Summary](#summary)
- [Objectives](#objectives)
- [Code of Conduct](#code-of-conduct)
- [Assignment Specification](#assignment-specification)

  - [Project Ideas](#project-ideas)
  - [Baseline Requirements](#baseline-requirements)

- [Project Proposal](#project-proposal)

- [Project Progress](#project-progress)

- [Project Submission](#project-submission)

- [Required Deliverables](#required-deliverables)

- [Assignment Assessment](#assignment-assessment)

- [System Commands](#system-commands)

  - [Using Docker](#using-docker)
  - [Using Gradle](#using-gradle)

- [Receiving Assistance](receiving-assistance)

## Summary

Designed for use with [GitHub Classroom](https://classroom.github.com/), this repository contains the starter files for the project assignment in Computer Science 310.

Throughout the semester, you have used various computational tools and techniques to explore a number of intelligent questions. The final project invites you to explore, in greater detail, a real-world application of artificial intelligence. You will research in more depth a real-world AI project that is interesting to you and carry out a computational investigation through the use, implementation, testing, and evaluation of different types of software.

For your final project, you can work individually or in groups of two or three. If you decide to work in a group, each member of the team will be evaluated separately based on his or her contributions to the project. This evaluation will be determined from the distribution of work as evidenced from progress discussion, project report and the feedback of the team members. You are also responsible for writing a detailed report, stored in the file `writing/report.md`. This is a Markdown file that must adhere to the standards described in the [Markdown Syntax Guide](https://guides.github.com/features/mastering-markdown/).

## Objectives

To explore, implement and test an AI application using the knowledge and skills developed in class. To experiment designing a learning agent for the chosen application by using appropriate algorithms and software. To evaluate the performance of the AI agent used in the application and to reflect on its task environment. To reflect on the work conducted for the project and to highlight ethical issues raised in the completed AI application.

## Code of Conduct

Throughout the completion of this project you must adhere to the community guidelines that we developed as a class. In addition to reporting any violations of the code of conduct, please make sure that you attest to the fact that you followed the code of conduct. Students who think that the class should revise some aspect of the guidelines must use the GitHub issue tracker for that repository to suggest, discuss, and implement any required changes.

## Assignment Specification

For the project assignment you may choose an AI problem that is of the most interest to you and can be investigated through computational technique(s). Pick something realistic and useful, for example, you can choose specific question(s) related to the topics we discussed in class. You may use anything and everything we have learned (or will learn) in class and you are expected to research additional resources beyond of what we discussed in class. You may also extend any of the programs or concepts we have developed in the labs or in class. However, the problem that you choose should not just be a copy of one of the lab assignments, or the class exercises, or the programs in the book with slight modifications. Remember, you must adhere to the Honor code! Please be original!

### Project Ideas

- Extend one of the labs.
- Implement a new feature in [facial recognition project](https://github.com/Allegheny-Ethical-CS/facial_recognition_bias).
- Implement a new feature in [predictive wellness project](https://github.com/Allegheny-Ethical-CS/predictiveWellness)
- Implement a new feature in [fake news detection project](https://github.com/Allegheny-Ethical-CS/FakeNewsDetection)
- Implement a "skill" for Misty robot.
- Implement an application using a Bebop drone.
- Implement an application using Google cardboard VR.
- Implement a new application motivated by class content.

### Baseline Requirements

1. Select a real AI application to investigate.
2. Research relevant background and find motivating references.
3. Identify and utilize computational techniques for implementing your application (you may use existing tools and/or develop programs).
4. Develop a learning agent to implement your application.
5. Testing of the implementation (either automated or manual). This should demonstrate that you tested your code.
6. Experiments and the underlying results. These should showcase how your application performs under various conditions.
7. Identify agent's task environment.
8. Identify and reflect on ethical considerations involving your application.
9. Demonstration of continuous work on the project as evidenced by the commits and work during lab sessions.

## Required Deliverables

This assignment invites you to submit the following deliverables through your team repository.

### Project Proposal

Develop a detailed proposal (at least 500 words) for your project including preliminary research on the importance of the application motivated by references. Write a description of what you propose to do for your project and share it with your instructor through your project GitHub repository. Your proposal should include at least three references that motivate the importance of the problem. You do not need to include any specifications on exactly how exactly you will implement your proposed application at this point, however you should discuss potential tools or algorithms you maybe able to utilize for your project.

Lab session on November 17th will be used for idea discussion and work time.

### Progress report

Describe everything you have done so far in your progress report of at least 1000 words. By this point, you should have conducted necessary research on the background of the application and made a significant progress towards implementing the solution to your proposed application. Describe anything new that you have learned so far and any unexpected challenges that you have encountered. Explain what implementation work you have completed and outline steps that are needed to complete this work, with an exact timeline of when you plan to accomplish each task.

Lab session on December 1st will be used for project work. Lab session on December 8th will be used for project walkthrough and work time.

### Final Submission

Your programs should be stored in the `src` directory, be well documented and conform to basic styling conventions. Your repository should have a modified README that contains detailed instructions on the tools and steps needed to run your system. Submissions without reproducible set up instructions will receive a grade reduction.

Your final report should highlight the key contributions of your work and consist of at least 2000 words (you are welcome to integrate text from your proposal and your progress report into your final report). The report should include a description of why the chosen application and solution is important and discuss the implementation that you undertook. The written material should be precise, formal, appropriately formatted, grammatically correct, informative, and interesting. In summary, your report should include:

- The motivation for your project. Why is the question you decided to address important and useful?
- Background for the proposed investigation. What have others done for it already? What resources have you used? Include references. Also identify PEAS and the type of environment (stochastic, dynamic, etc.) your agent operates in.
- Detailed description of the work you completed for this project. Provide algorithms if necessary. If you extended an existing project, clearly explain what new components you have contributed to.
- Testing that was conducted to ensure accuracy of your implementation.
- Sample output. You can include it directly in your report, or if it is lengthy, put it into a separate document and reference it in your report.
- Analysis of your experimental results. Make graphs, tables, snapshot of output, or anything else that can help us understand your results and incorporate them into your Markdown document.
- Conclusion. Give a short overview of your project and its results. Describe what you learned, what were the biggest challenges and the biggest rewards. and the results of the experiments that were run.

## Assignment Assessment

The grade that a student receives on this assignment will have the following components.

- **GitHub Actions CI Build Status [up to 5%]:**: For project repository associated with this assignment students will receive a checkmark grade if their last before-the-deadline build passes. This is only checking some baseline writing and commit requirements. An additional reduction will given if the commit log shows a cluster of commits at the end clearly used just to pass this requirement. An addition reduction will also be given if there is no commit during lab work times. All other requirements are evaluated manually.

- **Mastery of Verbal Explanation during Progress Walkthrough [up to 5%]:**: Since the timely project development and the ability to communicate technical details of a project is crucial to building successful software applications, a portion of students' project grade will be determined based on the quality of the project walkthrough based on the progress during the lab session on December 8th.

- **Mastery of Technical Writing [up to 20% (proposal 5%, progress 5%, report 10%)]:**: Students will also receive a checkmark grade when the responses to the writing questions presented in the `proposal.md`, `progress.md` and `report.md` reveal a proficiency of both writing skills and technical knowledge. To receive a checkmark grade, the submitted writing should address all required components and have correct spelling, grammar, and punctuation in addition to following the rules of Markdown and providing conceptually and technically accurate answers.

- **Mastery of Technical Knowledge and Skills [up to 70%]**: Students will receive the largest portion of their assignment grade when their project implementation reveals that they have mastered all of the technical knowledge and skills developed during the completion of this project. As a part of this grade, the instructor will assess aspects of the project including, but not limited to, the completeness and the correctness of the program(s), testing, the use of effective source code comments and Git commit messages, and the effective experimental analysis.

All grades for this project will be reported through a student's gradebook GitHub repository.

## System Commands

### Using Docker

Once you have installed [Docker Desktop](https://www.docker.com/products/docker-desktop), you can use the following `docker run` command to start `gradle grade` as a containerized application, using the [DockaGator](https://github.com/GatorEducator/dockagator) Docker image available on [DockerHub](https://cloud.docker.com/u/gatoreducator/repository/docker/gatoreducator/dockagator).

```bash
docker run --rm --name dockagator \
  -v "$(pwd)":/project \
  -v "$HOME/.dockagator":/root/.local/share \
  gatoreducator/dockagator
```

The aforementioned command will use `"$(pwd)"` (i.e., the current directory) as the project directory and `"$HOME/.dockagator"` as the cached GatorGrader directory. Please note that both of these directories must exist, although only the project directory must contain something. Generally, the project directory should contain the source code and technical writing of this assignment, as provided to a student through GitHub. Additionally, the cache directory should not contain anything other than directories and programs created by DockaGator, thus ensuring that they are not otherwise overwritten during the completion of the assignment. To ensure that the previous command will work correctly, you should create the cache directory by running the command `mkdir $HOME/.dockagator`.

If you are running your program on a Windows Operating System, you should run the following command instead, replacing the word "user" with the username of your machine:

```bash
docker run --rm --name dockagator -v "%cd%":/project -v "C:\Users\user/.dockagator":/root/.local/share gatoreducator/dockagator
```

Here are some additional commands that you may need to run when using Docker:

- `docker info`: display information about how Docker runs on your workstation
- `docker images`: show the Docker images installed on your workstation
- `docker container list`: list the active images running on your workstation
- `docker system prune`: remove many types of "dangling" components from your workstation
- `docker image prune`: remove all "dangling" docker images from your workstation
- `docker container prune`: remove all stopped docker containers from your workstation
- `docker rmi $(docker images -q) --force`: remove all docker images from your workstation

### Using Gradle

Since the above `docker run` command uses a Docker image that, by default, runs `gradle grade` and then exits the Docker container, you may want to instead run the following command so that you enter an "interactive terminal" that will allow you to repeatedly run commands within the Docker container.

In Linux and Mac OS:

```bash
docker run -it --rm --name dockagator \
  -v "$(pwd)":/project \
  -v "$HOME/.dockagator":/root/.local/share \
  gatoreducator/dockagator /bin/bash
```

In Windows OS (replace `user` with your machine's username):

```bash
docker run -it --rm --name dockagator -v "%cd%":/project -v "C:\Users\user/.dockagator":/root/.local/share gatoreducator/dockagator /bin/bash
```

Once you have typed this command, you can use the [GatorGrader tool](https://github.com/GatorEducator/gatorgrader) in the Docker container by typing the command `gradle grade` in your terminal.

## Receiving Assistance

If you are having trouble completing any part of this project, then please talk with the course instructor during the lab or class sessions. Alternatively, you may ask questions in the Discord workspace for this course. Finally, you can schedule a meeting during the course instructor's office hours.
