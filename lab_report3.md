LAB REPORT 3!

The command I chose to use is ```grep```! 

Alternative Command 1: ```grep -v```
- it searches for lines that do not match a pattern



Alternative Command 2: ```grep -n```
- it shows the matching lines along with the line numbers
~Example 1: a search for the word "LEGAL" in the government directory



```RyLees-MacBook-Pro:government ryleedavis$ grep -n "LEGAL" *
grep: About_LSC: Is a directory
grep: Alcohol_Problems: Is a directory
grep: Env_Prot_Agen: Is a directory
grep: Gen_Account_Office: Is a directory
grep: Media: Is a directory
grep: Post_Rate_Comm: Is a directory
```

Example 2: a search for the phrase "GOVERNMENT LAW" in the government directory


Alternative Command 3: ```grep -c```
-it counts the number of occurrences of a pattern

Alternative Command 4: ```grep -l```
- you can search through more than 1 file with this command! it shows only the filenames that contain a pattern you give it

- you can search through more than 1 file with this command! it shows only the filenames that contain a pattern you give it
~ Example 1: a more specific search of the word "PLANES" in the 911report directory
(below is the code and the output)
![Image 5-24-23 at 11 01 PM](https://github.com/oRyLee/Lab-Report-3/assets/130015533/5c03ddff-cbfe-40be-b410-da4a8bbe4d0c)


~ Example 2: a more broad search of the word "the" in the 911report directory
(below is the code and the output)


![Image 5-24-23 at 11 06 PM](https://github.com/oRyLee/Lab-Report-3/assets/130015533/4e030aec-1d00-4326-bfc7-6ef21a2bfcec)

