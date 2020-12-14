# Guideline for Group Project
>Due Date: 20 January 2021

## INSTRUCTION:

You are required to develop a program using __MAVEN__ and __Java__ programming language. 

1. Refer to the link below for the Telegram Bots.  

   https://core.telegram.org/bots


2. Create a Telegram Bots using the following format:
>STIW3054_GroupName_bot (Example: STIW3054_Kachi_bot)


3. Write Java methods to read a list of student from a Github Wiki page. Refer to the link below for the testing purpose.

   https://github.com/STIW3054-A201/Main-Data/wiki/List_of_Student (use this link for testing: https://github.com/STIW3054-A191/Assignments/wiki/List_of_Student)
 

4. Your program should be able to receive a MetricNo through Telegram Bots and return the following info.
   * The number of the given issues from https://github.com/STIW3054-A201/Main-Issues/issues. (use this link for testing: https://github.com/STIW3054-A191/Main-Issues/issues)
   * List of the issues' title and the number of students who have submitted the issues (refer to Assignment-1).
   * Count the number of submitted isssues for each student.
   * Count the percentage of the submitted isssues for each student. The percentage is based on the number of the given issues.
   * Display the name, number of the submitted issues and the percentage of the submitted issues.
   * Display all the unsubmitted issues' title.
   * List of the assignments' title and the number of students who have submitted the assignments
   * Count the number of submitted assignments for each student.
   * Count the percentage of the submitted assignments for each student. The percentage is based on the number of the given assignments.
   

## Example of input (from telegram bots):
```
262572
```

## Example of output (from telegram bots):

The format can be modified based on your creativity which is suitable for displaying at telegram.
```
Number of issues: 10

| Issue | Title                 | Number of students |
|-------|-----------------------|--------------------|
| 1     | Extending Thread      | 42                 | 
| 2     | Implementing Runnable | 27                 | 
| 3     | Method Reference      | 36                 | 
| 4     | .......               |                    | 

| No. | Matric | Name                    | Submitted Issues |Percentage |
|-----|--------|-------------------------|------------------|-----------|
| 1   | 261780 | Bu Yong Liu             | 10               | 100       |
| 2   | 262572 | Norfatiah Binti Amir    | 8                | 80        |


Number of assignments: 2

| Issue | Title                 | Number of students |
|-------|-----------------------|--------------------|
| 1     | Assignment-1          | 40                 | 
| 2     | Assignment-2.         | 36                 | 

| No. | Matric | Name                    | Submitted Assignment |Percentage |
|-----|--------|-------------------------|----------------------|-----------|
| 1   | 261780 | Bu Yong Liu             | 2                    | 100       |
| 2   | 262572 | Norfatiah Binti Amir    | 1                    | 50        |

Your request:

262572 Norfatiah Binti Amir
No: 2
Submitted Issues: 8 (80%)
Submitted Assignments: 1 (50%)

| Unsubmitted Issue | Title                 | 
|-------------------|-----------------------|
| 2                 | Implementing Runnable |
| 4                 | xxxxxxxx              |

| Unsubmitted Assignment | Title                 | 
|------------------------|-----------------------|
| 2                      | Assignment-2.         |

```
   
5. Your program should also meet the following requirements:
   * Each issue will be analyzed by __ONE (1)__ thread.
   * The number of current threads will be based on the number of processors in your laptop/machine.
   * If an issue takes more than 1 minute to respond, the process will be terminated. The terminated notification will be sent to your Telegram Bots.
   * (Additional requirements will be added later)

6. After completing the program, generate __UML Class Diagram__


## Testing
1. Send your Telegram's link to our Whatsapp group for the testing.
2. All students in our class will test and give feedback.


## SUBMISSION:

1. All source codes must be uploaded to the group's GitHub repository.
1. Video --> [IntelliJ IDEA | How to clone, add, commit and push a repository to GitHub easily](https://youtu.be/RXV3Yusr0SI)
1. All images must be included in `images` folder.
1. The screenshot of result/output must be displayed at your `Readme.md`.
1. The UML Class Diagram must be displayed at your `Readme.md`.
1. Record the implementation of the system and upload to YouTube. The video presentation MUST be in English (without the music) and not more than 10 minutes.  Then add the link to your `Readme.md`.
1. Write all references at your `Readme.md`. The references should not less than 20.
1. Upload your JavaDoc in the same repository. Video --> [Step-by-step | How to create a simple JavaDoc in IntelliJ IDEA](https://youtu.be/fAQB556HtiI)
1. To confirm the submission, paste your group's REPOSITORY link at the issue below:    
   https://github.com/STIW3054-A201/Assignments_and_Project/issues/3


## EVALUATION:

The marks will be given based on the:
1. The quality of the system.
2. The correctness of the results.
3. UML Class Diagram.
4. Video Presentation.
5. List of the reference (Not less than 20).
6. JavaDoc

## PLAGIARISM CHECK:

No mark will be given for plagiarism activities.


## LATE SUBMISSION:

Penalties will be given for each late submission.


## Guide for References Using APA Style:

https://libguides.umgc.edu/apa-examples
