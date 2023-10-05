# SQL-Server
Pivot the Occupation column in OCCUPATIONS so that each Name is sorted alphabetically and displayed underneath its corresponding Occupation. The output column headers should be Doctor, Professor, Singer, and Actor, respectively.
Note: Print NULL when there are no more names corresponding to an occupation.
Input Format
The OCCUPATIONS table is described as follows:
![image](https://github.com/ttng51/SQL-Server/assets/146753832/b016b0ba-53d6-4262-ae2b-e6114696b10f)

Occupation will only contain one of the following values: Doctor, Professor, Singer or Actor.
Sample Input
![image](https://github.com/ttng51/SQL-Server/assets/146753832/ca424568-f3dd-499c-bfc7-1ad8de748a56)

Sample Output
Jenny    Ashley     Meera  Jane
Samantha Christeen  Priya  Julia
NULL     Ketty      NULL   Maria

Explanation
The first column is an alphabetically ordered list of Doctor names.
The second column is an alphabetically ordered list of Professor names.
The third column is an alphabetically ordered list of Singer names.
The fourth column is an alphabetically ordered list of Actor names.
The empty cell data for columns with less than the maximum number of names per occupation (in this case, the Professor and Actor columns) are filled with NULL values.
