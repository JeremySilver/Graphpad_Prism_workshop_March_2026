# Effects of Serotonin in Mice: `MouseBrain.csv`
https://vincentarelbundock.github.io/Rdatasets/doc/Stat2Data/MouseBrain.html 

### Purpose
Demonstrating how you can run a two-way analysis of variance (ANOVA)

### Description

Effects of altering serotonin levels on social interactions of mice

### Format

A data frame with 48 observations on the following 3 variables.

* `Contacts`: Number of social contacts the mouse had during the experiment
* `Sex`: F=female or M=male
* `Genotype`: Minus, Mixed, or Plus (see description below)

### Details

Serotonin is a chemical that influences mood balance in humans. But how does it affect mice? Scientists genetically altered mice by "knocking out" the expression of a gene, tryptophan hydroxylase 2 (Tph2), that regulates serotonin production. With careful breeding, the scientists produced three types of mice that we label as "Minus" for Tph2-/-, "Plus" for Tph2+/+, "Mixed" for Tph2+/-. The variable Genotype records Minus/Plus/Mixed. The variable Contacts is the number of social contacts that a mouse had with other mice during an experiment and the variable Sex is "M" for males and "F" for females.

### Source

Beis D, Holzwarth K, Flinders M, Bader M, Wohr M, Alenina N., (2015) "Brain serotonin deficiency leads to social communication deficits in mice," Biol. Lett. 11:20150057. http://dx.doi.org/10.1098/rsbl.2015.0057

Once you go to the above link, to get the data, click on the "Figures and Data" tab. Then click on the "Juvenile SocInter Behavior Data" link to download a hairy data file that needs to be cleaned a great deal to get our data.

# Mucociliary efficiency: `three_group_comparison_data.csv`

### Description

Mucociliary efficiency from the rate of removal of dust in normal subjects, subjects with obstructive airway disease, and subjects with asbestosis.

### Format

A data frame with 14 observations on the following 2 variables.

* `mucociliary_efficiency`: rate of removal of dust 
* `group`: normal subjects, subjects with obstructive airway disease, or subjects with asbestosi* s

### Source

Myles Hollander and Douglas A. Wolfe (1973), Nonparametric Statistical Methods New York: John Wiley & Sons.  Pages 115-120.


# Student’s sleep data: `sleep_study.csv`

### Description
Data which show the effect of two soporific drugs (increase in hours of sleep compared to control) on 10 patients.

### Format

A data frame with 20 observations on 3 variables.

* `extra`:  (numeric) increase in hours of sleep (compared to control)
* `group`: (factor) drug given
* `ID`: (factor) patient ID

### Note

The 'group' variable name may be misleading about the data: They represent measurements on 10 persons, not in groups.

### Source:
Cushny, A. R. and Peebles, A. R. (1905) The action of optical isomers: II hyoscines.  The Journal of Physiology. 32, 501-510.
Student (1908) The probable error of the mean. Biometrika, 6, 20
