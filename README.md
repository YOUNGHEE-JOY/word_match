# Word matching cognitive experiment
# Project Purpose
This experiment was designed to understand how people store and process the meaning of 
words, concepts, and objects in their minds. In the experiment, participants are shown a
target word along with three choice words. They are asked to choose which word is most
related to the target. The goal is to measure how words are related in meaning (semantic
association) or how similar they are based on visual features.
Besides semantic meaning, the experiment also includes matching based on visual features
like color, size, texture, and shape. This helps compare semantic processing with
feature-based processing, to see which one is faster and more difficult.
For the semantic condition, there are two levels -
"high" (strongly related) and "low" (weakly
related). The experiment analyzes whether response time is significantly different between
these two levels. 
# Experiment design
All reactions of each participants are saved automatically. Each trial begins with a target word displayed near the top center of the screen.
Below the target word, the condition is shown to guide the participant’s decision. At
the bottom of the screen, three choice words are presented, labeled 1, 2, and 3 from
left to right. The participant reads the target word and selects the option that best
matches the given condition by pressing the corresponding number key (1, 2, 3).
There are six conditions-high,low, colour, size, texture, and shape.
Each condition contains 10 trials, and both the order of the six conditions and the 10
trials within each condition are randomized for each participant.
# Key Data Points
1. In each of the CSV files above, the following columns are recorded in order:
Condition, Target, Word1, Word2, Word3, Answer, CorrectAnswer, RT (Reaction
Time), IsCorrect, Time
2. combined
_
results.csv: This file contains the full response records from all
participants, merged into one file.
3. participant
_
results.csv: This file includes, for each condition, only the trials where
each participant selected the correct answer. It records the average reaction time,
standard error, and accuracy rate in order.
4. group_
results.csv: This file summarizes trials in which the correct answer was
chosen, grouped by condition. It records the average reaction time, standard error,
and accuracy rate for each condition.





