Task 2.6:
Transcriptomics

This is a processed RNAseq dataset involving reading in quantitated gene expression data from an RNA-seq experiment, exploring the data using base R functions and then interpretation. The dataset contains an experiment between a diseased cell line and diseased cell lines treated with compound X. The difference in expression change between the two health status is computed as Fold change to log 2 (Log2FC) and the significance of each is computed in p-value.

Access Dataset

Task:

Generate a volcano plot. (Hint search for volcano plot online)

Determine the upregulated genes (Genes with Log2FC > 1 and pvalue < 0.01)

Determine the downregulated genes (Genes with Log2FC < -1 and pvalue < 0.01)

What are the functions of the top 5 upregulated genes and top 5 downregulated genes. (Use genecards)

Task 2.7:
Public Health

NHANES is a program run by the CDC to assess the health and nutritional status of adults and children in the US. It combines survey questions and physical examinations, including medical and physiological measurements and laboratory tests, and examines a representative sample of about 5,000 people each year. The data is used to determine the prevalence of diseases and risk factors, establish national standards, and support epidemiology studies and health sciences research. This information helps to develop public health policy, design health programs and services, and expand the nation's health knowledge.

Dataset Data Dictionary

Tasks: Process all NA (either by deleting or by converting to zero) {Hard :feuer:} Visualize the distribution of BMI, Weight, Weight in pounds (weight *2.2) and Age with an histogram. What’s the mean 60-second pulse rate for all participants in the data?

73.63382

What’s the range of values for diastolic blood pressure in all participants? (Hint: see help for min(), max()).

0-116

What’s the variance and standard deviation for income among all participants?

Visualize the relationship between weight and height ?

Color the points by

gender
diabetes
smoking status
Conduct t-test between the following variables and make conclusions on the relationship between them based on P-Value
Age and Gender
BMI and Diabetes
Alcohol Year and Relationship Status
