# Instructions

**Please create your repository as part of this organization (sta440-fa21).**

### Deadline and submission

The project proposal will be due **Monday, September 20** (optional deadline).
An initial submission is due **Monday, November 22** (optional deadline). The
final submission is due **Wednesday, December 8**. All components are due 
11:59PM on their respective dates. Note that the proposal and initial draft
submissions are optional - however, I highly encourage you to turn in these
assignments, as you will receive feedback from the instructor. 

There is **no grace period** for the final manuscript due to the course's final
exam schedule. Sorry, instructions from above!

Your GitHub report repository and commit history will also be evaluated by the 
instructor. The GitHub repository must contain the reproducible R Markdown 
document corresponding to the submitted reports, and will be checked throughout 
the course of the project.

### Guidelines

- This is an individual assignment.
- Everything in your repository is for your eyes only except for the instructor
or TAs.
- As always, you must cite any code you use as inspiration. A failure to cite is
plagiarism.

### Academic integrity

By submitting an assignment, you pledge to uphold the Duke Community Standard:

- I will not lie, cheat, or steal in my academic endeavors;
- I will conduct myself honorably in all my endeavors; and
- I will act if the Standard is compromised.

# Data

The data used for your project should be uploaded to either the GitHub repository
or the Duke Computing cluster (depending on the size of the dataset). These
data must be shareable, as others will be reproducing your work. If there is
a compelling reason not to share the data (e.g., proprietary industry data),
please make that clear.

Students may provide their own data, with the understanding that these data 
should not have been analyzed previously as part of a course assignment or 
internship (if you would like to take a prior analysis to the next level, please 
provide the full prior analysis write-up with your proposal for evaluation). If
you are having trouble finding data, please contact the instructor as soon as
possible.

# Proposal (optional)

There are two main purposes of the project proposal: 

- To help you think about the project early, so you can get a head start on 
finding data, reading relevant literature, thinking about the questions you wish 
to answer, etc. 
- To ensure that the data you wish to analyze, methods you plan to use, and the 
scope of your analysis are feasible and will help you be successful for this 
project.

In writing your proposal, include an introduction (brief context, the motivation 
for your research question, any relevant literature citations, and the general 
research questions and hypotheses) and a description of the data that you will be
using (including any data use agreements and where the data came from). 

Note that your proposal does not have to be your final analysis! It is just meant
to get you started. It's possible that the scope of your project will change
throughout this semester.

The proposal should be **no more than 3 pages** at 11 point font or larger (figures
and tables not included). 

# Grading policy

**Your final score will only be based on your final submission**. If you do
choose to submit an initial draft, the instructor will provide feedback
including a numeric score, but this is intended solely as guidance.

A more detailed discussion of grading considerations is available after this
overview. The final report is worth 100 points, broken down as follows:

| Component    | Points |
|--------------|--------|
| Introduction | 20     |
| Methodology  | 30     |
| Results      | 20     |
| Discussion   | 30     |

You may create sub-headings as you like, but you must have these four 
components in your final report. 

Any grade deductions in appendices will be allocated to their appropriate
sections. For instance, appendix figures evaluating model assumptions may
impact points corresponding to Methodology and Results. Appendix figures 
displaying exploratory analyses or data cleaning steps may impact points
corresponding to Introduction, etc.

There may additionally be grade deductions for overall paper issues. For  
instance, make sure the paper is professionally presented and free of 
distracting errors or other issues such as poor organization, problems 
with grammar, spelling, or punctuation, and layout concerns such as small 
font in visuals, excessive and inappropriate decimal points, etc. (this 
is not an exhaustive list!).

# Grade considerations:

Note that simply “not making any errors” isn’t enough to get full points 
on an assignment - that is the baseline expectation! In line with Duke 
grade considerations, work earning an A is truly exceptional, and 
demonstrates fluent mastery of the statistical issues and presents 
convincing, well-organized results in a clear and appropriate way. Work
earning a B suggests superior understanding of the material, but may have 
some minor issues in its approach or communication. Work earning a C is
satisfactory and suggests adequate understanding - this is the baseline 
expectation. For a detailed list of grade considerations for each section, 
refer to the subsections following these paragraphs.

To use a statistical analogy in how I grade these assignments, I use sort 
of a forward/backward approach - there are aspects about each report which 
work well, and reports may “earn points” for that, and aspects which might 
be missing, insufficient, or incorrect (which correspondingly detract from 
the point total).  In order to earn additional points, I’m looking for a 
*comprehensive* treatment of the subject matter, well-justified statistical 
modeling choices with good explanation, clear and concise writing, and 
with a logical flow. Because of this, I start “in the middle” (well, more 
accurately, at a 75% baseline) and add or subtract points based on 
identified mistakes and strengths of the analysis.

To provide a concrete example, simply writing the correct model formulation 
for an appropriate model isn’t enough to get full credit - I *already expect* 
this of you! To earn full credit you must additionally justify the use of 
the model chosen in terms of its appropriateness, explain its use in context, 
and compare its strengths and weaknesses to other alternative methodologies.

After grading each case, I will provide a list of common errors (both minor 
and major), as well as comment on exceptional areas. Finally, note that my
grading standards will "get tougher" as the semester goes on. While including
"p = 0.0000" is considered a minor mistake and result in a small deduction in 
the Results section (is the p-value *actually* zero? If not, provide it to the
accuracy actually obtained, e.g., "p < 0.0001"), making this error on Case 3
would result in a larger grade penalty than on Case 1.

### Introduction

The introduction should introduce your general research question and your data
(where it came from, how it was collected, what the observational unit is, 
which variables were used in the analysis, etc. Feel free to create subsections 
as needed (for instance, for the dataset, any exploratory visualizations, etc.). 

In evaluating your introduction, I will be evaluating the following points:

- Is/are the main goal(s) of the analysis easy to identify and appropriate for
addressing the overall research problem?
- Is the rationale for the data analysis explained well?
- Does the manuscript describe the context/background of the work and its 
relation to existing literature?
- Are the variables (response and predictors) clearly identified and discussed?
- Does the manuscript explain how the data were collected and/or how they were
derived?
- If provided, is any EDA helpful and informative in addressing the main 
project goal(s)?

### Methodology

The methodology section should clearly explain the model(s) used in your 
analysis. You must clearly state your model formulation using appropriate
mathematical notation and justify their use, and address any model assumptions 
or diagnostics needed. 

In evaluating your methodology, I will be evaluating the following points:

- Is the proposed analysis appropriate given the main goal(s) and dataset?
- Why was this particular methodology chosen over competing choices?
- Are the specific methods described in enough detail that the work could be
replicated by other researchers *without* access to the original analysis code?
- Is it clear which approaches/models were used to evaluate specific goals?
- What assumptions are needed for the model(s), and how do you plan to assess
whether they hold?
- What sensitivity analyses, if any, are planned, and how do they relate to your
analysis approach?

You may include technical derivations and evaluation of model diagnostics and
assumptions in the appendix to your manuscript; they do not belong in the body
of your work.

### Results

Showcase your results! Provide model output (such as coefficient estimates and
quantification of uncertainty) in tabular and/or visual format. Make sure that
each set of results presented supports the goal(s) of your manuscript.

In evaluating your results, I will be evaluating the following points:
 
- Are tables formatted cleanly and precisely? Do visualizations follow good
practices (e.g., clean axis labels, clear titles, appropriate figures given
data types, etc.)?
- Do tables/figures refer to raw variable names, or are all references clearly
made in context of the data?
- Are appropriate conventions re: formatting (e.g., an acceptable number of
decimal places, table/figure captions, etc.) followed when displaying results?
- Is there an appropriate quantification of uncertainty of estimates?
- Are all results interpreted correctly? 

### Discussion

Discuss the implications your results have in terms of your goal(s) and research
question(s). As well, provide a reasoned critique of your methodology and 
provide suggestions for improving the analysis or what additional data might
have strengthened the paper. 

In evaluating your discussion, I will be evaluating the following points:

- How do your results address or fail to address the goal(s) of your manuscript?
- Does the manuscript provide clear, correct, and effective interpretation of
the analysis results?
- Are all conclusions made directly supported by the results?
- Was your methodology fully appropriate? What alternative techniques might have
been useful?
- Are there any issues with reliability or validity of the data?
- What would you do differently if you had to approach the study again? What
additional data sources, variables, or techniques might help you create a 
stronger manuscript?

### Appendix

This is where you present any technical derivations (if needed) and demonstrate
that the assumptions for your models are met. Examples of derivations might
include explicit variance terms of frequentist estimators or derivation of
full conditional distributions for Gibbs samplers, etc.

As for examples of assumptions, if you are creating a linear model, this would be
a good place to discuss the assumptions (e.g., by providing residual plots and
comments); if you are performing a Bayesian analysis, this would be a good place
to show diagnostic plots (e.g., trace plots, etc.). This section may be as long 
or as short as needed. 

### Repository

The instructor will also evaluate whether the commit history is appropriate and
contains clear descriptions of each committed change. This repository must
contain all code used, as well as any ancillary external files which you may
have used in your analysis.

The final .pdf report must be typeset and reproducible from your analysis code
(end-to-end scripting). This .pdf must match your submission to Gradescope. 

### Tips

- **Make sure you are addressing the case study goals.**
- Clearly state your hypothesis (or hypotheses) - think about how your paper
might create actionable insight for others.
- Make sure you use best visualization practices as discussed in class for all
visualizations and/or tables.
- Write clearly and effectively; confusing the reader is never a good thing!
- Quality over quantity - do not calculate every statistic and procedure you 
have learned for every variable, but rather choose the most *appropriate*
technique or set of techniques to address the goal at hand.
- Focus on methods that help you begin to answer your research questions.
