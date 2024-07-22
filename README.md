# Module-04-Homework

In this challenge, I successfully completed most of the requirements by applying what I learned about Pandas in the classes and utilizing the provided starter code. The only part where I encountered trouble was in the "Scores by School Spending" section, where I needed to do calculation using data from the "per_school_summary" dataframe that had been formatted in an earlier section. However, the columns' data types were converted to objects after formatting, and calculations can't be done won object data type. I consulted ChatGPT on how to convert objects with leading or trailing signs to numerical type, and I applied the syntax that ChatGPT provided. It worked, but then I noticed that the converted data kept only two decimal places because of the formatting applied earlier. Due to the missing decimals, the calculation results are slightly different from the results shown in the provided starter code. Eventually, I found help on how to solve this issue from the resource listed below. The resource gave me the idea to create a copy of the raw dataframe before formatting it so that I could easily refer back to the unformatted data later.

Resources that I referred to for completing this part:

<https://github.com/saraparveen26/Pandas---PyCitySchools/blob/main/PyCitySchools/PyCitySchools_solved.ipynb>

<https://chatgpt.com/>

## Analysis (Written Report)

The required written report is in the file "PyCitySchools.ipynb".
