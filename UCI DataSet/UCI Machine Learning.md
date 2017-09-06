#### This is a markdown document which consists of the details of the UCI Machine Learning Data Set

## Name of the Data Set
**_San Francisco State University  
   Software Engineering Team Assessment and Prediction (SETAP) Project_**

## Interesting Aspect in the Data Set
> This data is specifically used to demonstrate the viability of using ML on objective and quantitative team activity measures to predict student learning of software engineering 
teamwork, and point to easy-to-measure factors that can be used to guide educators and software engineering managers to implement early intervention for teams bound to fail

## Data Description
  The following is a detailed description of the data contained in the
  accompanying files.

  INTRODUCTION
  ------------

  The data contained in these files were collected over a period of
  several semesters from students engaged in software engineering
  classes at San Francisco State University (class sections of CSC
  640, CSC 648 and CSC 848).  All students consented to this data
  being shared for research purposes provided no uniquely identifiable
  information was contained in the distributed files.  The information
  was collected through various means, with emphasis being placed on
  the collection of objective, quantifiable information.  For more
  information on the data collection procedures, please see the paper
  referenced above.


  PRIVACY
  -------
  The data contained in this file does not contain any information
  which may be individually traced to a particular student who
  participated in the study.


  BRIEF DESCRIPTION OF DATA SOURCES AND DERIVATIONS
  -------------------------------------------------
  SAMs (Student Activity Measure) are collected for each student team
  member during their participation in a software engineering class.
  Student teams work together on a final class project, and comprise
  5-6 students.  Teams that are made up of students from only one
  school are labeled local teams.  Teams made up of students from more
  than one school are labeled global teams.  SAMs are collected from:
  weekly timecards, instructor observations, and software engineering
  tool usage logs.  SAMs are then aggregated by team and time interval
  (see next section) into TAMs (Team Activity Measure).  Outcomes are
  determined at the end of the semester through evaluation of student
  team work in two categories:  software engineering process (how well
  the team applied best software engineering practices), and software
  engineering product (the quality of the finished product the team
  produced).  Thus for each team, two outcomes are determined, process
  and product, respectively.  Outcomes are classified into two class
  grades, A or F.  A represents teams that are at or above
  expectations, F represents teams that are below expectations or need
  attention.  For more information, please see the paper referenced
  above.

  The SE process and SE product outcomes represent ML training classes
  and are to be considered separately, e.g. one should train ML for SE
  process separately from training for SE product.

  TIME INTERVALS FOR WHICH DATA IS COLLECTED
  ------------------------------------------
  Data collected continuously throughout the semester are aggregated
  into different time intervals for the semester's project reflecting
  different dynamics of teamwork during the class.  Time intervals
  represent time periods in which a milestone was developed by each
  team.  A milestone represents a major deliverable point in the class
  for all student teams.  The milestones are roughly divided into the
  following topics:

            M1 - high level requirements and specs
            M2 - more detailed requirements and specs
            M3 - first prototype
            M4 - beta release
            M5 - final delivery

  Time intervals are combinations of the time in which milestones are
  being produced.  Time intervals are used in research only.

  In addition to time intervals corresponding to milestones, a number
  of time intervals combining multiple T1-T5 time intervals have been
  calculated.  This was done to group student activities into design
  vs. implementation phases which have different dynamics.

  These time intervals are defined as follows:
      Time Interval        Corresponding Milestone Periods in Class
    -----------------    --------------------------------------------
  *         0               Milestone 0
  *         1               Milestone 1
  *         2               Milestone 2
  *         3               Milestone 3
  *         4               Milestone 4
  *         5               Milestone 5
  *         6               Milestone 1 - Milestone 2 inclusive
  *         7               Milestone 1 - Milestone 3 inclusive
  *         8               Milestone 1 - Milestone 4 inclusive
  *         9               Milestone 1 - Milestone 5 inclusive
  *        10               Milestone 4 - Milestone 5 inclusive
  *        11               Milestone 3 - Milestone 5 inclusive


## LICENSE OR TERMS OF USE
This data is released under the Creative Commons Attribution-NonCommercial 4.0 International license.  For more information, please see [LICENSE](http://creativecommons.org/licenses/by-nc/4.0/legalcode)
The research that has made this data possible has been funded in part by NSF grant NSF-TUES1140172.

## Potential Data Users and Decision-makers for this data
Individuals or Organizations which have an interest in analyzing various effective methods for software engineering processes being followed as part of team activities
For research on various methods involved in software engineering processes

## Potential questions/information that can be obtained from this data set
1. How many project teams were successful and how many are failed
2. What is the average personal meeting hours for successful projects
3. In which semester was the success rate more

## References
Lichman, M. (2013). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.


