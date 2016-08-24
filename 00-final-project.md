Introduction
============

Team members for the experimental study are Minhchau Dang, Sue Yang, and Chuck Bolin. The project could not have been completed in its current state without the help of research assistants Carter Lin and Grace Bolin.

Motivation
----------

Students at all levels ranging from high school to advanced PhD studies are required to read a variety of documents ranging from literature, news articles, published papers, and academic texts. These requirements are stipulated throughout a course of study in the form of assignments.

Reading assignments issued by the teacher will include the name of the document along with a number of pages to read. In many cases the student is tasked with completing the reading with very little guidance, if any.

Imagine one is assigned to read a 30 page technical document describing Google File System followed by the instruction, "Be prepared to discuss in class."

This assignment presents a quandary to the student. What should the student take away from the reading? Is a high-level understanding of the file system sufficient, or does the teacher care about the functional level of connecting several computers? Should the student memorize countless details or gloss over them? The expectation is finally clarified when the class meets to actually discuss the reading. If the students failed to read the teacher's mind then this may feed a negative view of the student, or the student may feel that the preparation time was wasted.

Details are important! Or perhaps they are not? It depends upon the people involved in the contractual agreement to read and discuss the text.

Personality
-----------

Personality means the combination of characteristics or qualities that form an individual's distinctive character. It is believed to be formulated by the time a child enters first grade \[1\]. A long established method of describing personality is through the use of the Myers-Briggs Type Indicator (MBTI) instrument \[2\]. The test instrument uses 93 forced-choice questions to express a personality into four MBTI dichotomies \[3\].

![Four MBTI Dichotomies](images/dichotomies.jpg)

Upon completing the test, each individual is given a report describing their personality type \[4\]. A personality type is expressed as a four character combination \[5\], such as ENFP, INFP, and INTP, with each character indicating your preference in each of the four MBTI dichotomies.

The focus of this research paper is on the Sensing-Intuition dichotomy. This dichotomy indicates whether a person is high or low detailed when approaching information \[6\], and the two sides are described as follows:

-   **Sensing (high-detail)**: "I notice facts and I remember details that are important to me."
-   **Intuition (low-detail)**: "I remember events more as an impression of what it was like than as actual facts or details of what happened."

When aggregating by dichotomy, 26.9% of the population are Intuition (low-detail), while Sensing (high-detail) commands a largely disproportionate value of 73.1%. This is significant when comparing the proportions of the other three attributes which tend to have a more balanced ratio.

When we aggregate by dichotomy, we find that 26.9% of the population are Intuition (low-detail) with Sensing (high-detail) commanding a largely disproportionate value of 73.1%. This is significant when comparing the proportions of the other three attributes which tend to comprise a more balanced ratio.

![](00-final-project_files/figure-markdown_github/population_percentage-1.png)

Research Questions
------------------

Do unguided reading assignments risk discriminating against 26.9% of the population--the Intuition (low-detail) people?

In order to answer this larger question, this team designed an experiment that addresses three primary sub-questions.

1.  Are the populations different from each other in a reading recall task?
2.  Is there a treatment effect through the use of guidance for the reading?
3.  Is this effect different between Sensing (high-detail) and Intuitive (low-detail) personalities?

In operationalizing the research questions, our experiment will explicitly look at the following:

1.  Do Sensing (high-detail) personality types outperform Intuitive (low-detail) personality types on reading recall tasks when no instructions are provided?
2.  Does a study guide accompanying the reading assignment improve reading recall for both personality types?
3.  Is the improvement in recall from the study guide different between the two personality types?

Hypothesis
----------

The team hypothesizes that under experimental conditions evaluating memory recall of information from a reading assignment, Sensing (high-detail) subjects would score higher than Intuition (low-detail) subjects in the control group (without guidance).

When provided with guidance (the treatment), it is hypothesized that both groups will score higher than their counterparts in the control group. Furthermore, it is proposed that Intuition (low-detail) personality will improve more than Sensing (high-detail) personality, thus reducing the gap between the two personality types.

Experimental Design
===================

Definition of Treatment
-----------------------

The key difficulty for a person tasked with a reading assignment is the uncertainty of knowing the parts of the reading upon which to focus. Therefore the treatment is presented in the form of a primer.

In the primer provided to the control group, the participants would be given the following paragraph *without guidance*.

> You will be given 6 minutes to read an article. Be prepared to answer some questions.
>
> ***Thank you for your participation in this experiment. Please do not share details of the experiment with others as it may compromise the usefulness of the final results.***

In the primer provided to the treatment group, the participants would be given the following paragraph *with guidance*.

> You will be given 6 minutes to read an article. Be prepared to answer some questions.
>
> ***You do NOT need to know facts related to dates (years, months, or days) referenced in the article. You do NOT need to know the names of any entertainers.***

These sentences are written in order to minimize any potential effect due to awareness of being in a treatment or control group in a group session setting, in the event that a participant glances at another participant's primer.

Experimental Sequence
---------------------

The following sequence of events describes the experiment. It is applicable to administration to individuals or to groups of subjects.

1.  Subjects arrive and are welcomed. Subjects are reminded not to discuss details of the experiment for four weeks.
2.  Subjects read the "Consent to Participate in Research" form, ask any relevant questions, and sign the document.
3.  Subjects complete the online "Personality Test". The subjects are assigned a unique ID number and their personality types (e.g. INTJ-A) are recorded.
4.  The researcher references a pre-generated block randomization based upon the Sensing (high-detail) or Intuition (low-detail) personality type results and assigns each subject to a control or treatment group.
5.  Subjects are provided either a control or treatment primer (based on their group assignment) and are directed to read it. Subjects are provided an “Article” and given six minutes to read it.
6.  Subjects are given a "Covariate Questionnaire". In addition to providing basic information the questionnaire serves as a purposeful disruption in the cognitive process of memory recall before being queried on the reading assignment.
7.  Subjects are given a 40 question "Reading Recall Questionnaire", informed on the grading approach (awarded 1 point for a correct response, lose 1 point for an incorrect response, and 0 points if they chose not to answer), and allotted six minutes to complete the task.
8.  Subjects are thanked and reminded not to discuss details of the experiment for four weeks. If conducted on paper, the researcher enters the results of the personality tests and both questionnaires into an online form connected to Google Sheets.

The procedure for the steps described above are diagrammed below.

![Experimental Sequence](images/experimental_sequence.png)

Reading Considerations
----------------------

The first task is to identify an appropriate reading for the experimental subjects. When evaluating potential reading materials, the following factors are deemed relevant:

-   **Reading Level**: Materials are to be chosen at reading level that contains a significant number of details without being too esoteric. Using the Flesch-Kincaid Reading Ease algorithm \[7\], an article that scored grade 12.8 was selected.
-   **Neutral content**: The material does not include information that may alienate the subject. Therefore, topics such as religion and politics were excluded. To quote one subject’s concern about the reading assignment prior to the experiment, "It's not about witchcraft or the devil, is it?"
-   **Length**: The length of the reading is an important factor. If it is too long, the subject may grow weary. If it is too short, the subjects’ personality resistance to the number of details may be insufficiently exercised. A word count of approximately 700 words in a six-minute period is sufficient when considering the average reading speed for adults. \[8\]. An article from an encyclopedia about the National Broadcasting Company, Inc. \[9\] was chosen for the experiment.

Other Considerations
--------------------

The team agreed upon the description of the experiment as a "Personality vs. Reading" study. This language was to be used in email, telephone, and in-person requests for volunteers. Disclosure of details such as specifying high and low detail personality types was avoided, including the word "recall" in order to not cue participants to memorize details.

When examining the parameters of experimentation, whether it should be conducted online or in-person only, the researchers were cognizant that an online participant's study style might compel them to refer back to a locally saved copy of the text if taken on-line. This aspect could affect proper randomization, such as an uneven distribution of these individuals between treatment and control or between Sensing (high-detail) and Intuition (low-detail) personalities. Therefore, it was decided to conduct the experiment in-person only.

When conducting in-person experiments, the team determined whether subjects should be tested one at a time in order to ensure consistency across subjects, or if the team should allow for larger groups for efficiency. A single subject could be tested at a cost of approximately 35 minutes, or a large group of subjects could be tested at a cost of about one hour. The team opted to allow for group testing, and to treat a single subject as an extra small group.

The method of assessment was another concern. The team discussed multiple choice and true/false type of questions. It was agreed that a true/false questionnaire would accommodate single and group testing scenarios, and it would greatly simplify analysis as it would exclude variation as to which wrong answer was preferred.

During the experiment, questions from the subject were taken prior to signing the "Consent to Participate in Research". After this point, we limited our speech to administrative directions. This would allow us to minimize any potential differences between researchers with respect to their interactions with the subjects.

Design Description
------------------

The experiment is described with the following table using the notation suggested by the Web Center for Social Research Methods \[10\]:

<table>
<colgroup>
<col width="18%" />
<col width="16%" />
<col width="20%" />
<col width="16%" />
<col width="8%" />
<col width="18%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Region</th>
<th align="left">Personality Test</th>
<th align="left">Sensing vs Intuitive</th>
<th align="left">Assignment</th>
<th align="left">Treated</th>
<th align="left">Collect Test Score</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">N (South Carolina)</td>
<td align="left">O</td>
<td align="left">N (Sensing)</td>
<td align="left">R (Block S1-T)</td>
<td align="left">X</td>
<td align="left">O</td>
</tr>
<tr class="even">
<td align="left"></td>
<td align="left">O</td>
<td align="left"></td>
<td align="left">R (Block S1-C)</td>
<td align="left"></td>
<td align="left">O</td>
</tr>
<tr class="odd">
<td align="left"></td>
<td align="left">O</td>
<td align="left">N (Intuitive)</td>
<td align="left">R (Block N1-T)</td>
<td align="left">X</td>
<td align="left">O</td>
</tr>
<tr class="even">
<td align="left"></td>
<td align="left">O</td>
<td align="left"></td>
<td align="left">R (Block N1-C)</td>
<td align="left"></td>
<td align="left">O</td>
</tr>
<tr class="odd">
<td align="left">N (California)</td>
<td align="left">O</td>
<td align="left">N (Sensing)</td>
<td align="left">R (Block S2-T)</td>
<td align="left">X</td>
<td align="left">O</td>
</tr>
<tr class="even">
<td align="left"></td>
<td align="left">O</td>
<td align="left"></td>
<td align="left">R (Block S2-C)</td>
<td align="left"></td>
<td align="left">O</td>
</tr>
<tr class="odd">
<td align="left"></td>
<td align="left">O</td>
<td align="left">N (Intuitive)</td>
<td align="left">R (Block N2-T)</td>
<td align="left">X</td>
<td align="left">O</td>
</tr>
<tr class="even">
<td align="left"></td>
<td align="left">O</td>
<td align="left"></td>
<td align="left">R (Block N2-C)</td>
<td align="left"></td>
<td align="left">O</td>
</tr>
<tr class="odd">
<td align="left">N (Delaware)</td>
<td align="left">O</td>
<td align="left">N (Sensing)</td>
<td align="left">R (Block S3-T)</td>
<td align="left">X</td>
<td align="left">O</td>
</tr>
<tr class="even">
<td align="left"></td>
<td align="left">O</td>
<td align="left"></td>
<td align="left">R (Block S3-C)</td>
<td align="left"></td>
<td align="left">O</td>
</tr>
<tr class="odd">
<td align="left"></td>
<td align="left">O</td>
<td align="left">N (Intuitive)</td>
<td align="left">R (Block N3-T)</td>
<td align="left">X</td>
<td align="left">O</td>
</tr>
<tr class="even">
<td align="left"></td>
<td align="left">O</td>
<td align="left"></td>
<td align="left">R (Block N3-C)</td>
<td align="left"></td>
<td align="left">O</td>
</tr>
</tbody>
</table>

The nonrandom and random groups are identified as follows:

-   The location of the subject (South Carolina, California, Delaware) is not a random variable manipulated by the researchers.
-   The personality test result is not a random variable manipulated by the researchers.
-   The subject is assigned to either control or treatment using pre-generated randomized lists (block randomization) that were created for each personality type at each location. This is a random variable manipulated by the researchers.

Analysis Precheck
=================

Statistical Power
-----------------

Prior to commencing the analysis of the experiment, the researchers want to know whether or not there is a chance of detecting an effect. To do that, the average score and the standard deviation of that score must be identified for the control population.

In assuming that the control and treatment have similar variance, then if the team wanted 80% power in detecting a score difference between the control and treatment groups, the groups would need to be properly sized. The following table describes the result of using the `pwr.t.test` function to compute the needed sample size to detect the given true difference:

    ##   true.difference needed.size current.power
    ## 1             0.5        2241    0.08020943
    ## 2               1         561     0.1747189
    ## 3             1.5         250     0.3331124
    ## 4               2         141     0.5308397
    ## 5             2.5          91     0.7212663
    ## 6               3          64     0.8634363
    ## 7             3.5          47     0.9457718
    ## 8               4          36     0.9827614

An area of concern is the heterogeneous treatment effect, where the effective sample size is actually the number of people in treatment. The treatment group comprises half the number of people, and in this case, the heterogeneous effect is likely to be smaller than the base treatment effect. This yields the following table:

    ##    true.difference needed.size current.power
    ## 1              0.2       28002    0.05231686
    ## 2              0.4        7002    0.05930536
    ## 3              0.6        3113    0.07107133
    ## 4              0.8        1752    0.08776545
    ## 5                1        1122     0.1095477
    ## 6              1.2         780      0.136543
    ## 7              1.4         574     0.1687932
    ## 8              1.6         440     0.2062117
    ## 9              1.8         348     0.2485451
    ## 10               2         282     0.2953489

Verify Randomization
--------------------

During the next step, placebo tests were performed to confirm that the assignment to treatment and control groups is random. In these tests, it must be verified that being in treatment is not highly correlated with any variables, thus providing a confidence level that there is internal validity in the randomization.

In the first placebo test, a comparison is made regarding the personality dichotomy balance between the treatment and control groups.

![](00-final-project_files/figure-markdown_github/mbti_balance-1.png)

Verify Need for Clustered Design
--------------------------------

Four researchers conducted the experiment in three locations around the United States. Consequently there existed the possibility of between group variation, thus making it harder to estimate the average treatment effect precisely.

Additionally, one concern was there would be an effect from the slight variations between the way the experiment might be administered by each experimenter in each region. For example, in South Carolina and Delaware, the questionnaires were administered on paper, while in California the questionnaire was administered electronically.

In the experimental design description, the randomization planned for three different clusters based on the states. Because of the small sample size, the team wanted to know if the groups were actually different from each other, and thus whether the researchers benefited from this additional layer of complexity or if it would make more sense to simply pool the results.

### Variation Between Regions

A Levene's test was conducted to confirm homoskedasticity of the variances within each of the populations, and the result is not significant. Thus, the team is unable to reject the null hypothesis that the errors are homoskedastic. When the ANOVA test was run to compare the group means by region, the team also sees that it is unable to reject the null hypothesis that the group means are different.

The following table gives the results of these test runs:

    ## Levene's Test for Homogeneity of Variance (center = median)
    ##       Df F value Pr(>F)
    ## group  2  1.4905 0.2321
    ##       72

    ## Analysis of Variance Table
    ## 
    ## Response: Adjusted.Score
    ##           Df Sum Sq Mean Sq F value Pr(>F)
    ## Region     2  104.9  52.456  0.9689 0.3844
    ## Residuals 72 3898.2  54.142

Therefore at a regional level, there is no benefit gained from these distinct clusters because there is little difference between the clusters.

Variation Between Experimenters
-------------------------------

Before merging the data set, there may be a variation between the four different people administering the questionnaires. In South Carolina, there were two different people administering the experiment.

A Levene's test was conducted to confirm homoskedasticity of the variances within each of the populations, and the result is not significant. Thus, the team is unable to reject the null hypothesis that the errors are homoskedastic. When the ANOVA test was run to compare the group means by experimenter, the team also sees that it is unable to reject the null hypothesis that the group means are different.

The following table gives the results of these test runs:

    ## Levene's Test for Homogeneity of Variance (center = median)
    ##       Df F value Pr(>F)
    ## group  3  1.0446 0.3782
    ##       71

    ## Analysis of Variance Table
    ## 
    ## Response: Adjusted.Score
    ##              Df Sum Sq Mean Sq F value Pr(>F)
    ## Experimenter  3  107.4  35.794  0.6524 0.5841
    ## Residuals    71 3895.8  54.870

Therefore at an experimenter level, the team does not gain any benefit from these distinct clusters because the findings reveal little difference between clusters.

Pooled Results Design
---------------------

Because testing by region and testing by experimenter indicates that there is little variation between the groups we created, the team opts to pool the data from the different regions and experimenters, yielding the following experimental design:

| Personality Test | Sensing vs Intuitive | Assignment    | Treated | Collect Test Score |
|------------------|----------------------|---------------|---------|--------------------|
| O                | N (Sensing)          | R (Block S-T) | X       | O                  |
| O                |                      | R (Block S-C) |         | O                  |
| O                | N (Intuitive)        | R (Block N-T) | X       | O                  |
| O                |                      | R (Block N-C) |         | O                  |

Covariate Check
===============

The next step is to look at the covariates that were collected in the "Covariate Questionnaire". As they were unrelated to treatment, the team expects that there will be no correlation with treatment variables. However, the team expects that these covariates will explain some of the variance in the outcome.

Treatment Variable
------------------

First, the team examined the covariate balance between treatment and control.

![](00-final-project_files/figure-markdown_github/covariate_check_treatment-1.png)

The visualization points out that being younger may cause some preference in ending up in the treatment group. Given that we tested many variables, it is expected that at least one would to turn up significant. Other than that, the differences between groups appear random, so the team is willing to believe that our randomization worked and there is internal validity in the experimental design.

Outcome Variable
----------------

Next, the team examined how well these features predict the outcome.

    ##         name   F value      Pr(>F)
    ## 1:    gender 0.9048655   0.4091471
    ## 2:       age  1.655036   0.1982713
    ## 3: education  3.532256 0.006681307
    ## 4:  studying 0.1131372   0.8931866
    ## 5:  learning  1.463431   0.2382419
    ## 6:   reading 0.2813032   0.7556251

Among the ANOVA test results, `score ~ education` has significant result. (F value is 3.532, and p-value is very low too.)

This ANOVA result suggests that the variation of scores between different education levels is much larger than the variation of score within each education level. Our p-value is less than 0.05, indicating that the confidence interval does not include zero. Hence it is reasonable to reject the null hypothesis and assume that there is a relationship between score and education level.

Results Summary
===============

Statistical Power
-----------------

Using the formula for power in the Green and Gerber "Field Experiments" book \[11\], the team computed the expected statistical power for the experiment based on the sample.

    ## [1] 0.1330942

Statistical power with 75 subjects was calculated to be 0.133. Additionally, running the Shapiro-Wilk test on the outcomes indicates that the data is unlikely to be normally distributed, indicating that the power computations may need to be more complicated.

    ## 
    ##  Shapiro-Wilk normality test
    ## 
    ## data:  df.complete$adjusted.score
    ## W = 0.95932, p-value = 0.01674

Given this information, any potential causality is very unlikely to be stated conclusively.

Results for Control Group
-------------------------

The first question for this experiment was as follows:

> 1.  Do Sensing (high-detail) personality types outperform Intuitive (low-detail) personality types on reading recall tasks when no instructions are provided?

The alternate hypothesis predicted that there would be a statistically significant difference between Sensing (high-detail) and Intuition (low-detail) subject scores within the control group. The corresponding null hypothesis is that there is no statistically significant difference between Sensing (high-detail) and Intuition (low-detail) subject scores within the control group.

The alternate hypothesis also indicated a direction: Sensing (high-detail) subject scores would be greater than Intuition (low-detail) subject scores. Therefore, with a more generous outlook, a one-tailed t-test is sufficient.

    ## 
    ##  Welch Two Sample t-test
    ## 
    ## data:  adjusted.score by energy
    ## t = 1.6639, df = 34.34, p-value = 0.9474
    ## alternative hypothesis: true difference in means is less than 0
    ## 95 percent confidence interval:
    ##      -Inf 8.733758
    ## sample estimates:
    ## mean in group Intuition   mean in group Sensing 
    ##                15.07143                10.73913

The t-test of the mean scores of the Sensing (high-detail) and Intuition (low-detail) subjects within the control group had a p-value of 0.9474. Therefore, even with the more generous one-tailed t-test, the experiment failed to reject the null hypothesis.

A closer examination of the mean scores suggests that Intuition (low-detail) subjects in the control group scored higher than Sensing (high-detail) subjects in the control group, though the difference is not significant due to the high variance in the sample.

    ##       energy     mean       sd
    ## 1:   Sensing 10.73913 9.357629
    ## 2: Intuition 15.07143 6.450573

Results for Treatment Group
---------------------------

The second question for this experiment was as follows:

> 1.  Does a study guide accompanying the reading assignment improve reading recall for both personality types?

The alternate hypothesis predicted that there would be a statistically significant difference between control group and the treatment group for both the Sensing (high-detail) subjects and the Intuition (low-detail) subjects. The corresponding null hypothesis is that there is no statistically significant difference between the treatment and the control group for both the Sensing (high-detail) subjects and the Intuition (low-detail) subjects.

Rejecting this null hypothesis requires two t-tests: one to reject the null hypothesis concerning the Sensing (high-detail) subjects and one to reject the null hypothesis concerning the Intuition (low-detail) subjects.

The alternate hypotheses also indicate a direction: in both cases, the experiment anticipates an increase. Therefore, with a more generous outlook, a one-tailed t-test is sufficient.

The first t-test checks the null hypothesis concerning Sensing (high-detail) subjects.

    ## 
    ##  Welch Two Sample t-test
    ## 
    ## data:  adjusted.score by in.treatment
    ## t = -1.592, df = 38.517, p-value = 0.05978
    ## alternative hypothesis: true difference in means is less than 0
    ## 95 percent confidence interval:
    ##       -Inf 0.2207161
    ## sample estimates:
    ##   mean in group Control mean in group Treatment 
    ##                10.73913                14.50000

The second t-test checks the null hypothesis concerning Intuitive (low-detail) subjects.

    ## 
    ##  Welch Two Sample t-test
    ## 
    ## data:  adjusted.score by in.treatment
    ## t = 0.72973, df = 26.256, p-value = 0.764
    ## alternative hypothesis: true difference in means is less than 0
    ## 95 percent confidence interval:
    ##      -Inf 5.451593
    ## sample estimates:
    ##   mean in group Control mean in group Treatment 
    ##                15.07143                13.43750

The third t-test checks the null hypothesis concerning the two groups in the aggregate.

    ## 
    ##  Welch Two Sample t-test
    ## 
    ## data:  adjusted.score by in.treatment
    ## t = -0.98083, df = 64.236, p-value = 0.1652
    ## alternative hypothesis: true difference in means is less than 0
    ## 95 percent confidence interval:
    ##      -Inf 1.174555
    ## sample estimates:
    ##   mean in group Control mean in group Treatment 
    ##                12.37838                14.05263

In all cases, the t-test results are not significant and the experiment is unable to reject any of the null hypotheses.

A closer examination of the mean scores suggests that the treatment results in a decrease in the mean score for Intuition (low-detail) subjects and an increase in the mean score for the (high-detail) subjects, though the difference is not significant due to the high variance in the sample.

    ##       energy in.treatment     mean       sd
    ## 1: Intuition      Control 15.07143 6.450573
    ## 2: Intuition    Treatment 13.43750 5.715112
    ## 3:   Sensing      Control 10.73913 9.357629
    ## 4:   Sensing    Treatment 14.50000 6.246904

Results for Heterogeneous Treatment Effect
------------------------------------------

The third question for this experiment was as follows:

> 1.  Is the improvement in recall from the study guide different between the two personality types?

This heterogeneous treatment effect can be tested using linear regression. The team will use the following model in order to predict the adjusted score:

\[
AdjustedScore_i = \beta_0 + \beta_1 Sensing_i + \beta_2 InTreatment_i + \beta_3 InTreatment_i \times Sensing_i
\]

For a subject \(i\), \(AdjustedScore_i\) corresponds to the subject's adjusted score from the questionnaire, \(Sensing_i\) corresponds to whether the person has a Sensing (high-detail) personality type, and \(InTreatment_i\) corresponds to whether the subject was provided with the treatment primer.

For reference purposes, the model will be evaluated against a model leveraging only \(Sensing_i\) and against a model leveraging both \(Sensing_i\) and \(InTreatment_i\) using `stargazer` \[12\]:

<table style="text-align:center">
<caption>
<strong>Energy and Treatment</strong>
</caption>
<tr>
<td colspan="4" style="border-bottom: 1px solid black">
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td colspan="3">
<em>Dependent variable:</em>
</td>
</tr>
<tr>
<td>
</td>
<td colspan="3" style="border-bottom: 1px solid black">
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td colspan="3">
Adjusted Score
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
(1)
</td>
<td>
(2)
</td>
<td>
(3)
</td>
</tr>
<tr>
<td colspan="4" style="border-bottom: 1px solid black">
</td>
</tr>
<tr>
<td style="text-align:left">
Sensing
</td>
<td>
-1.622
</td>
<td>
-1.551
</td>
<td>
-4.332<sup>\*</sup>
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
(1.735)
</td>
<td>
(1.738)
</td>
<td>
(2.472)
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td style="text-align:left">
Treatment Primer
</td>
<td>
</td>
<td>
1.608
</td>
<td>
-1.634
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
(1.703)
</td>
<td>
(2.669)
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td style="text-align:left">
Sensing x Treatment Primer
</td>
<td>
</td>
<td>
</td>
<td>
5.395
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
</td>
<td>
(3.443)
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td style="text-align:left">
Constant
</td>
<td>
14.200<sup>\*\*\*</sup>
</td>
<td>
13.342<sup>\*\*\*</sup>
</td>
<td>
15.071<sup>\*\*\*</sup>
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
(1.344)
</td>
<td>
(1.623)
</td>
<td>
(1.949)
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td colspan="4" style="border-bottom: 1px solid black">
</td>
</tr>
<tr>
<td style="text-align:left">
Observations
</td>
<td>
75
</td>
<td>
75
</td>
<td>
75
</td>
</tr>
<tr>
<td style="text-align:left">
R<sup>2</sup>
</td>
<td>
0.012
</td>
<td>
0.024
</td>
<td>
0.057
</td>
</tr>
<tr>
<td style="text-align:left">
Adjusted R<sup>2</sup>
</td>
<td>
-0.002
</td>
<td>
-0.003
</td>
<td>
0.017
</td>
</tr>
<tr>
<td style="text-align:left">
Residual Std. Error
</td>
<td>
7.361 (df = 73)
</td>
<td>
7.367 (df = 72)
</td>
<td>
7.293 (df = 71)
</td>
</tr>
<tr>
<td style="text-align:left">
F Statistic
</td>
<td>
0.874 (df = 1; 73)
</td>
<td>
0.882 (df = 2; 72)
</td>
<td>
1.418 (df = 3; 71)
</td>
</tr>
<tr>
<td colspan="4" style="border-bottom: 1px solid black">
</td>
</tr>
<tr>
<td style="text-align:left">
<em>Note:</em>
</td>
<td colspan="3" style="text-align:right">
<sup>*</sup>p&lt;0.1; <sup>**</sup>p&lt;0.05; <sup>***</sup>p&lt;0.01
</td>
</tr>
</table>
Causal Findings
---------------

The results are not significant, so the team was unable to draw any causal conclusions from this experiment.

Applications and Future Research
================================

Solidifying the Result
----------------------

Past research indicated a lack of statistically significant result when comparing Sensing (high-detail) personality types and Intuitive (low-detail) personality types in nursing \[13\], as well as an improvement for Intuitive (low-detail) personality types in engineering \[14\].

Still, the research team was surprised that the group means (while not statistically significant) were the opposite of what was hypothesized given the specific questions that were presented and the specific task under evaluation, particularly with respect to how additional details appeared to lower scores for Intuitive (low-detail) personality types.

    ##       energy in.treatment     mean       sd
    ## 1: Intuition      Control 15.07143 6.450573
    ## 2: Intuition    Treatment 13.43750 5.715112
    ## 3:   Sensing      Control 10.73913 9.357629
    ## 4:   Sensing    Treatment 14.50000 6.246904

Given the lack of statistical power, this may have been a case of regression to the mean. Additional follow up will be needed in order to evaluate the model.

Going on a Fishing Expedition
-----------------------------

In our covariate checks, the team observed that there was a statistically significant correlation between our outcome variable and education.

For an individual \(i\), if we let \(education_{i1}\) indicate if the individual finished education after completing high school, \(education_{i2}\) indicate if the individual finished their education after receiving an associate's degree, \(education_{i3}\) indicate if the individual finished their education after 3+ years without receiving a degree, \(education_{i4}\) indicate if the individual received a bachelor's degree, and \(education_{i5}\) indicate if the individual finsihed their education after receiving a master's degree or higher.

We compare the models to see if adding education as a variable reduces the variance in the terms \(Sensing_i\) and \(InTreatment_i\).

<table style="text-align:center">
<caption>
<strong>Fishing Expedition</strong>
</caption>
<tr>
<td colspan="4" style="border-bottom: 1px solid black">
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td colspan="3">
<em>Dependent variable:</em>
</td>
</tr>
<tr>
<td>
</td>
<td colspan="3" style="border-bottom: 1px solid black">
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td colspan="3">
Adjusted Score
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
(1)
</td>
<td>
(2)
</td>
<td>
(3)
</td>
</tr>
<tr>
<td colspan="4" style="border-bottom: 1px solid black">
</td>
</tr>
<tr>
<td style="text-align:left">
energySensing
</td>
<td>
-4.332<sup>\*</sup>
</td>
<td>
</td>
<td>
-3.135
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
(2.472)
</td>
<td>
</td>
<td>
(2.354)
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td style="text-align:left">
in.treatmentTreatment
</td>
<td>
-1.634
</td>
<td>
</td>
<td>
-1.748
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
(2.669)
</td>
<td>
</td>
<td>
(2.490)
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td style="text-align:left">
energySensing:in.treatmentTreatment
</td>
<td>
5.395
</td>
<td>
</td>
<td>
5.666<sup>\*</sup>
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
(3.443)
</td>
<td>
</td>
<td>
(3.248)
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td style="text-align:left">
education1
</td>
<td>
</td>
<td>
-10.300<sup>\*\*\*</sup>
</td>
<td>
-11.190<sup>\*\*\*</sup>
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
(3.349)
</td>
<td>
(3.377)
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td style="text-align:left">
education2
</td>
<td>
</td>
<td>
-7.800<sup>\*\*</sup>
</td>
<td>
-7.671<sup>\*\*</sup>
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
(3.510)
</td>
<td>
(3.582)
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td style="text-align:left">
education3
</td>
<td>
</td>
<td>
0.200
</td>
<td>
-1.108
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
(4.021)
</td>
<td>
(4.075)
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td style="text-align:left">
education4
</td>
<td>
</td>
<td>
-0.894
</td>
<td>
-1.446
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
(2.462)
</td>
<td>
(2.459)
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td style="text-align:left">
education5
</td>
<td>
</td>
<td>
-0.550
</td>
<td>
-1.568
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
(2.740)
</td>
<td>
(2.788)
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td style="text-align:left">
Constant
</td>
<td>
15.071<sup>\*\*\*</sup>
</td>
<td>
15.300<sup>\*\*\*</sup>
</td>
<td>
17.000<sup>\*\*\*</sup>
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
(1.949)
</td>
<td>
(2.149)
</td>
<td>
(2.704)
</td>
</tr>
<tr>
<td style="text-align:left">
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td colspan="4" style="border-bottom: 1px solid black">
</td>
</tr>
<tr>
<td style="text-align:left">
Observations
</td>
<td>
75
</td>
<td>
75
</td>
<td>
75
</td>
</tr>
<tr>
<td style="text-align:left">
R<sup>2</sup>
</td>
<td>
0.057
</td>
<td>
0.204
</td>
<td>
0.250
</td>
</tr>
<tr>
<td style="text-align:left">
Adjusted R<sup>2</sup>
</td>
<td>
0.017
</td>
<td>
0.146
</td>
<td>
0.159
</td>
</tr>
<tr>
<td style="text-align:left">
Residual Std. Error
</td>
<td>
7.293 (df = 71)
</td>
<td>
6.797 (df = 69)
</td>
<td>
6.745 (df = 66)
</td>
</tr>
<tr>
<td style="text-align:left">
F Statistic
</td>
<td>
1.418 (df = 3; 71)
</td>
<td>
3.532<sup>\*\*\*</sup> (df = 5; 69)
</td>
<td>
2.749<sup>\*\*</sup> (df = 8; 66)
</td>
</tr>
<tr>
<td colspan="4" style="border-bottom: 1px solid black">
</td>
</tr>
<tr>
<td style="text-align:left">
<em>Note:</em>
</td>
<td colspan="3" style="text-align:right">
<sup>*</sup>p&lt;0.1; <sup>**</sup>p&lt;0.05; <sup>***</sup>p&lt;0.01
</td>
</tr>
</table>
The addition of education does not reduce the variance in any of the variables in our original model. We do, however, note that the \(R^2\) is substantially higher for education alone than for either of the variables selected for our original model.

Conclusions
===========

The experiment answered the teams research questions to some extent, but the experiment did not yield the expected conclusions and the answers were not statistically significant.

> 1.  Do Sensing (high-detail) personality types outperform Intuitive (low-detail) personality types on reading recall tasks when no instructions are provided?

No. Rather, from the current sample data, Intuition (low-detail) personality types appear to outperform Sensing (high-detail) personality types on reading memory recall questions. However, this difference is not statistically significant.

> 1.  Does a study guide accompanying the reading assignment improve reading recall for both personality types?

In the aggregate, the population performs better on reading memory recall questions after guidance is provided that narrows the focus of the reading assignment. However, this difference is not statistically significant.

> 1.  Is the improvement in recall from the study guide different between the two personality types?

Intuitive (low-detail) personality types end up with lower scores after receiving the treatment, while Sensing (high-detail) personality types end up with higher scores. However, this difference is not statistically significant.

References
==========

\[1\] “Personality set for life by 1st grade, study suggest” \[Online\]. Available: <http://www.livescience.com/8432-personality-set-life-1st-grade-study-suggests.html>. \[Accessed: 20-Aug-2016\]

\[2\] “Myers-briggs type indicator” \[Online\]. Available: <https://en.wikipedia.org/wiki/Myers%E2%80%93Briggs_Type_Indicator>. \[Accessed: 20-Aug-2016\]

\[3\] “The 4 dichotomies/8 differences” \[Online\]. Available: <http://16-personality-types.com/mbti-four-dichotomies/>. \[Accessed: 20-Aug-2016\]

\[4\] “Free personality test, NERIS type explorer” \[Online\]. Available: <https://www.16personalities.com/free-personality-test>. \[Accessed: 20-Aug-2016\]

\[5\] “The 16 personality types - which is your type?” \[Online\]. Available: <http://www.careerplanner.com/MB2/16-Types-Traditional.cfm>. \[Accessed: 20-Aug-2016\]

\[6\] “MBTI basics, sensing or intuition” \[Online\]. Available: <http://www.myersbriggs.org/my-mbti-personality-type/mbti-basics/sensing-or-intuition.htm>. \[Accessed: 20-Aug-2016\]

\[7\] “Measure text readability” \[Online\]. Available: <https://readability-score.com/text/>. \[Accessed: 20-Aug-2016\]

\[8\] “Do you read fast enough to be successful?” \[Online\]. Available: [www.forbes.com/sites/brettnelson/2012/06/04/do-you-read-fast-enough-to-be-successful](www.forbes.com/sites/brettnelson/2012/06/04/do-you-read-fast-enough-to-be-successful). \[Accessed: 20-Aug-2016\]

\[9\] “National broadcasting company inc.” *International Directory of Company Histories*, 1990 \[Online\]. Available: <http://www.encyclopedia.com/topic/National_Broadcasting_Company_Inc.aspx>. \[Accessed: 04-Jul-2016\]

\[10\] “Introduction to design” \[Online\]. Available: <http://www.socialresearchmethods.net/kb/desintro.php>. \[Accessed: 20-Aug-2016\]

\[11\] A. S. Gerber and D. P. Green, *Field experiments: Design, analysis, and interpretation*. W. W. Norton & Company, 2012.

\[12\] M. Hlavac, *Stargazer: Well-formatted regression and summary statistics tables*. Cambridge, USA: Harvard University, 2015 \[Online\]. Available: <http://CRAN.R-project.org/package=stargazer>

\[13\] “Relationships between the myers-briggs type indicator personality profiling, academic performance and student satisfaction in nursing students,” *International Journal of Bio-Science and Bio-Technology*, vol. 6, no. 6, 2014 \[Online\]. Available: <http://www.sersc.org/journals/IJBSBT/vol6_no6/1.pdf>. \[Accessed: 20-Aug-2016\]

\[14\] “Myers-briggs type indicator and academic achievement in engineering education,” *International Journal of Engineering Education*, vol. 14, no. 5, 1998 \[Online\]. Available: <http://www.ijee.ie/articles/Vol14-5/ijee1039.pdf>. \[Accessed: 20-Aug-2016\]
