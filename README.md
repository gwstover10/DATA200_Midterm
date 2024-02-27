# DATA200_Midterm
## Midterm Project - Show What you Know!
Due February 27

Description

Purpose: Apply the concepts learned in the first half of this course to an interesting data set.
Choose your own path and demonstrate your mastery of the learning objectives!

A collection of dataset sources is described at the end of this document, mainly from Kaggle
and from my own research. Feel free to find data sets from other sources, as long as they require
some regex and have plety of oportunities for grouping and aggregating! The data cannot be
data that has already been used in this course. The data must be available publicly.

Your submission should be a single pdf (exported from a Jupyter notebook) uploaded to
GradeScope. Groups must be two to four people (inclusive). Absolutely no groups larger than
4, and groups of 1 are similarly discouraged.

The next page includes a rubric for how the project will be graded. The list below is a much
more concise description of what I want.

• A clear research question that can be answered by the data available to you.

• An exploratory data analysis, including cleaning and visualization that are rele-
vant to the research question. Make sure everything is relevant to the goal of the project!
No extraneous plots!

• Clever use of regex to wrangle some text data.

• Use of information from multiple sources (e.g. joining together data sets)

• Clever use of split-apply-combine (groupby and aggregating)

• Some basic modelling. The modelling should hint at a more interesting modelling
approach, but does not need to be in-depth.

• General life advice: Make it easy for people to help you. For this project, make it easy
to mark. Happy graders hive higher grades!!!

## Rubric
• Cohesion
1. Submission consists of disconnected applications of course material.
2. It is clear why each aspect of the submission is present, but there is no clear direc-
tion.
3. The submission has a clear overarching idea.
4. All aspects of the submission work together to answer a single, clear research ques-
tion.

• Code Cells
1. Notebook is either mostly code or mostly text, including irrelevant output.
– “Irrelevant output” refers to any outputs from code that is never mentioned in
the text. Adding superfluous references to the output does not make it relevant.
2. Notebook includes reasonable amounts of code and text, but includes irrelevant
code/output.
3. Notebook is well structured, with code used in appropriate places.
4. Notebook is well structured, with clean, readable code and clear, concise interpre-
tations of the code.

• Regex Application
1. Regex not used.
2. Regex only uses basic syntax.
– For example, “*“,”|“, etc., which could be replaced by find-and-replace or
som”or” statements.
3. Regex is required; a simpler solution would not work.
4. Regex syntax could validate an email address.
– (Not actually, but the regex is involved and takes more than a quick glance to
understand).

• Regex Usefulness
1. Regex wasn’t necessary
– For example, simply searching for the word “opposition” can be done with an
in statement.
2. Regex used a single wildcard or pattern.
3. Regex use was necessary and correct.
4. Regex was used in an interesting way. The project could not have been completed
without it.
– (The regex should be either used to explore the data set, filter the data to relevant
observations, or it may define the target and/or response variable.)

• Split-Apply-Combine
1. Not used or use was not meaningful.
2. Used, but output was not meangingful or was not interesting.
– For example, df.groupby("Name").sum() is not an interesting use of groupby,
even if the output is very informative.
3. Groupby operations are applied well in meaningful contexts.
4. Groupings are applied in a creative way, leading to deeper insights.

• Augmentation
1. Only a single data set was used.
2. A second data set was joined to the first, but the result did not enhance the project.
3. Information from a second data set was used to enhance the main data being stud-
ied.
4. A second data set with relevant information was identified and the result signifi-
cantly enhanced the analysis.

• Visualization aesthetics
1. Matplotlib plotting defaults are used. Way too few or way too many plots are
included.
2. Plots are labelled, but poorly. Too few or too many plots are included.
3. Only the relevant plots are present, with proper labelling.
– Again, “irrelevant” means a plot that’s present in the code but not mentioned
in the text.
4. All relevant plots are present and are well labelled. Code is concise, and gestalt
principles (colours, shapes, axis labels, etc.) are applied correctly.

• Visualization Content
1. Plots are inappropriate or insuﬀicient for the given data.
– For example, using a dot plot when a bar plot should have been used, or using
a pie chart with many many categories.
2. Appropriate plots are used, but do not show the whole picture.
– For example, bar charts for data that can be further subdivided, or scatterplots
that could be colour coded.
3. Appropriate plots are used.
4. Choice of visualization reveals deeper insights while still displaying the data faith-
fully.

• Basic Modelling
1. Models not fit.
2. Models are fit to data, but results do not reveal any insights.
3
3. Models are fit to the data and some insights are explored.
4. Models reveal interesting insights, with proper interpretations of the parameters.
While not complete, the model is a first step in a thorough analysis.

• Content Descriptions
1. Notebook contains a lot of irrelevant information or is clearly missing information.
2. Notebook would benefit from editing or editorializing, such as removing/combining
sections or adding new sections.
3. Notebook is a reasonable length; all information is present and nothing extra is
present.
4. Notebook contains exactly the information needed, presented concisely and com-
pletely.

• Benefit-of-the-Doubt Marks
– Each project will be given 3 marks by default.
– Marks can be removed for major errors not covered by this rubic, such as not
including names or submitting an assignment with errors (or no outputs).
• Available Bonus Marks
– (2 marks) Notebook is hosted publicly on GitHub, GitLab, Bitbucket, etc.
∗ Be careful not to include personal information - such as student numbers -
in the version hosted publicly. Your GradeScope submission should have this
information, but not the version on GitHub.
– Up to 2 marks can be added for extra creativity in the data cleaning or presentation
