# An Empirical Study on Cleansed Workarounds in Apache Projects

## Project summary

In software development, issue tracker systems are widely used to manage bug reports. In such a system, a bug report can be filed, diagnosed, assigned, and fixed. In the standard process, a bug can be resolved as *fixed*, *invalid*, *duplicated* or *won't fix*. Although the above resolutions are well-defined and easy to understand, a bug report can end with a less known resolution, i.e., *workaround*. Compared with other resolutions, the definition of workarounds is more ambiguous. Besides the problem that is reported in a bug report, the resolution of a workaround raises more questions. Some questions are important for users, especially those programmers who build their projects upon others (*e.g.*, libraries). Although some early studies have been conducted to analyze API workarounds, many research questions on workarounds are still open. For example, which bugs are resolved as workarounds? Why is a bug report resolved as workarounds? What are the repairs and impacts of workarounds? In this paper, we conduct the first empirical study to explore the above research questions. In particular, we analyzed 200 real workarounds that were collected from 81 Apache projects. Our results lead to eight findings and our answers to all the above questions. For example, we find that if bug reports are resolved as workarounds, their problems most likely arise across projects (40%) or reside in environments (23.5%). Although the problems of some workarounds (38.5%) reside in the project where they are reported, it is difficult to fix them fully and perfectly. Our findings are useful to understand workarounds and to improve software projects and issue trackers.

## Dataset

In this paper, we analyze 221 real workarounds that were collected from 88 Apache projects. 21 of them are filtered out, so the dataset only contains 200 cleansed workarounds from 81 Apache projects.

## Result

File "Workaround.txt" can be opened by Excel.

"Workaround.txt" is a table recording the 200 cleansed workarounds and their data. 

Each line except the first line corresponds to a bug report. The URL of each bug report can be accessed by adding the JIRA ID after "https://issues.apache.org/jira/browse/", for example: 

https://issues.apache.org/jira/browse/BEAM-6460

The columns:

- **ID**: The JIRA ID.

- **Symptom**: The symptom of the bug.

- **Cause**: The cause of using workaround to resolve the bug.

- **Repair**: The repair method of the workaround.

- **time_to_resolve**: The number of hours used to resolve the bug.

- **n_watchers**: The number of watchers of the bug report.

- **n_comments**: The number of comments of the bug report.

- **n_issuelinks**: The number of issue links of the bug report.

- **Priority**: The priority of the bug.

- **Project**: The project that the bug belongs to.