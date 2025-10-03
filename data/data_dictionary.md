# 📖 Data Dictionary – BREMEN BIKE GmbH Sales Dataset

This document describes the fields in the sales dataset used for the dashboard project.

| Column Name        | Description                                      | Type        | Notes |
|--------------------|--------------------------------------------------|-------------|-------|
| Customer_ID        | Unique identifier for each customer              | Integer     | Primary key in dataset |
| Marital_Status     | Customer marital status                          | Categorical | Values: Married, Single |
| Gender             | Customer gender                                  | Categorical | Values: Male, Female |
| Age                | Customer age (years)                             | Integer     | Range: 25–89 |
| Age_Group          | Derived age band                                 | Categorical | Groups: Young Adults, Middle Age, etc. |
| Income             | Annual income (Euros)                            | Currency    | 10,000–170,000 |
| Income_Group       | Derived income band                              | Categorical | Low, Lower-Middle, Middle, Upper-Middle, High |
| Commute_Distance   | Reported commute distance to work/school         | Categorical | Original values: 0-1, 1-2, 2-5, 5-10, 10+ Miles |
| Commute_Distance_Group | Normalized commute distance band             | Categorical | Derived from Commute_Distance |
| Education          | Customer education level                         | Categorical | e.g., High School, Bachelors, Graduate |
| Occupation         | Customer occupation                              | Categorical | e.g., Skilled, Professional |
| Purchase           | Bike purchase indicator (1 = Purchase, 0 = No)   | Boolean     | Target variable |
