# Dataset description

[Kaggle Link for dataset](https://www.kaggle.com/c/shaastra-wells-fargo-hackathon/data)
The dataset provides demographic data on the students of a University in Canada.

The information is organized in rows, where each row specifies the number of students enrolled (unique headcount) with each combination of attributes.

The information includes:

- Year - 2008-09 to 2015-16
- Term type - Fall term, spring term, winter term
- Degree type - Undergraduate, Graduate
- Program level - Doctoral, Masters, Non degree and Bachelors
- Study year - D (Doctoral), M (Masters), 1, 2, 3, 4
- Faculty grouping - ARTS, ENG (engineering), SCI (Science), MATH etc.
- Program grouping - Economics, Psychology, Mechanical engineering etc.
- Term type - Academic, Co-op
- Work Term - Academic term, Work term
- Attendance - Full-Time, Part-Time
- Visa status - Canadian, International, Canadian Permanent Resident
- Gender
The goal of this competition was to predict the unique headcount of students enrolled in each program based on their gender and other attributes associated with the program.

The train and test datasets are split based on time: training data from 2008-09 to 2015-16, while test data are from 2016-17.

## File description
wells_fargo_train.csv - the training set
wells_fargo_test.csv - the test set
wells_fargo_sample_submission.csv - a sample submission file in the correct format
