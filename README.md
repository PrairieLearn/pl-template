## PrairieLearn Course Repository

### Welcome to PrairieLearn! 

The content for your course is stored within this repository.
You can see and edit a live version at <https://prairielearn.engr.illinois.edu/>.

### Overview

PrairieLearn stores data for a course using folders and JSON files. 
Each of these files can be edited directly using the [PrairieLearn website's "Files" or "Settings" tab](https://prairielearn.engr.illinois.edu/). 
The roles of each file and directory are:

- **[infoCourse.json](infoCourse.json)**: Stores basic information about the course such as its number and name, e.g. PL 101: Using PrairieLearn.
- **[courseInstances/](courseInstances/)**: Directory containing per-semester offerings of a course, e.g. Fall 2020 and Spring 2021.
   - **[courseInstances/Fa20/infoCourseInstance.json](courseInstances/Fa20/infoCourseInstance.json)**: The upcoming Fall 2020 semester is found here. Make sure to set when the course should open and list the course's teaching staff.
   - **[courseInstances/Fa20/assessments](courseInstances/Fa20/assessments)**: Any assessment such as homework or exams for the Fall 2020 semester will be located here. These assessments are specific to the single-time course offering.
- **[questions/](questions/)**: All questions created for a course are found here. 
   - **[questions/sampleMultipleChoice](questions/sampleMultipleChoice)**: Inside of the **[questions/](questions/)** directory, one sample multiple choice question is present. The question is designed to show a new answer on each subsequent attempt of the question. For creating your own questions, we recommend until you get familiar with the system to use template questions as a base, which can be found in the Example Course (XC 101).
   
Questions or assessments may be copied from within the web interface by visiting either the 'Questions' or 'Assessments' space of a course. 
Inside the respective space, the copy action is achieved by: 

1. Clicking on the desired question or assessment name
2. Navigating to the 'Settings' tab (to the right of the 'Preview' or 'Regrading' tab)
3. Pressing 'Make a Copy of This Question/Assessment'.

### Reference Guide

[![](https://coatless.github.io/pl-cheatsheets/pngs/pl-authoring-cheatsheet-overview.png)](https://coatless.github.io/pl-cheatsheets/pdfs/prairielearn-authoring-cheatsheet.pdf)

### Getting help

Need help understanding an error or creating content? Check out one of the following resources:

1. Real-time help assistance on PrairieLearn's [Slack `#pl-help` channel](https://prairielearn.slack.com).
1. Looking up the question on our [Frequently Asked Question (FAQ) page](https://prairielearn.readthedocs.io/en/latest/faq/).
1. Attend an in-person or virtual office hours, which are announced at the start of the
   semester on PrairieLearn's [Slack](https://prairielearn.slack.com) and [e-mail listserv](https://lists.illinois.edu/lists/info/prairielearn-announce).
