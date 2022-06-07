# An Empirical Study on Cleansed Workarounds in Apache Projects

## Project summary

In software development, issue tracker systems are widely used to manage bug reports. In such a system, a bug report can be filed, diagnosed, assigned, and fixed. In the standard process, a bug can be resolved as *fixed*, *invalid*, *duplicated* or *won't fix*. Although the above resolutions are well-defined and easy to understand, a bug report can end with a less known resolution, i.e., *workaround*. Compared with other resolutions, the definition of workarounds is more ambiguous. Besides the problem that is reported in a bug report, the resolution of a workaround raises more questions. Some questions are important for users, especially those programmers who build their projects upon others (*e.g.*, libraries). Although some early studies have been conducted to analyze API workarounds, many research questions on workarounds are still open. For example, which bugs are resolved as workarounds? Why is a bug report resolved as workarounds? What are the repairs and impacts of workarounds? In this paper, we conduct the first empirical study to explore the above research questions. In particular, we analyzed 200 real workarounds that were collected from 200 Apache projects. Our results lead to nine findings and our answers to all the above questions. For example, we find that most bug reports are resolved as workarounds, because their problems arise across projects (40%) or reside in environments (23.5%). Although the problems of some workarounds (38.5%) reside in the project where they are reported, it is difficult to fix them fully and perfectly. Our findings are useful to understand workarounds and to improve software projects and issue trackers.

## Dataset

In this paper, we analyze 200 real workarounds that were collected from 81 Apache projects.

## Result

For each workaround, we provide its JIRA ID, symptoms, causes and repairs.

For each workaround and fixed issue, we also provide its time needed to resolve the issue, the number of watchers, the number of comments, its priority and project. This statistics are used in RQ5.

File "Workaround.txt" and "Fixed.txt" can be opened by Excel.