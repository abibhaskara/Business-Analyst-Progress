## Introduction
In this folder, i started to build a foundation for data analyst skill. I decided to make my own learning path for becoming a data analyst.

I started with 00 - foundation because I want to make sure that I have a strong foundation before moving on to more advanced topics.

## Structure
foundation: Basic concepts and tools using Microsoft Excel
    - IF
    - DATEDIF
    - VLOOKUP / HLOOKUP
    - REPLACE / SUBSTITUTE
    - UPPER / LOWER / PROPER
    - CONCAT
    - TRIM
    - AVERAGE
    - COUNT
    - SUM
    - MIN / MAX

Learn Common Functions
    - Charting
    - Pivot Tables

## Journal
I will use this section to document my learning process.

### 2/11/2026:
Personally, i have a stong fondation in microsoft excel and i'm confident that i can master this skill quickly. I've done several work using microsoft excel to help me organize and do some calculation. I know how to use several function of excel, but not all of it. So in this session, i take a quiz using gemini to test my knowledge of the basic function of excel.

On 1st attempt, I got 4/10 which mean i need to improve my basic function knowledge. The summary says I'm good at Text Manipulation (REPLACE vs SUBSTITUTE, TRIM & CONCAT): You demonstrate a strong understanding of core text transformation techniques, correctly identifying the difference between position-based replacement and string substitution, as well as handling spacing with TRIM and CONCAT. Data Visualization & Pivot Table Structure: You correctly identified appropriate chart selections for part-to-whole relationships (Pie chart) and understand the role of the Values quadrant for aggregating numbers in Pivot Tables.

Foocus Area:
Date & Lookup Functions (DATEDIF & VLOOKUP): Review unit parameters in DATEDIF (e.g., 'M' returns total calendar months, whereas 'YM' ignores years) and ensure you use FALSE (or 0) for exact matches in VLOOKUP to prevent approximate lookup errors.

Summary, Counting & Logical Functions (COUNT, AVERAGE, IF): Keep in mind that COUNT strictly evaluates numeric values (ignoring text and blanks, unlike COUNTA). Also practice breaking down nested logic step-by-step when evaluating conditional IF statements.
Text Case Functions & Pivot Table Scope: Remember that PROPER capitalizes the first letter of *every* word, not just the first. Revisit the foundational role of Pivot Tables as data aggregation and restructuring tools.

On 2nd attempt, I got 13/20 (sum from the previous test, if it substract and only took the result from my 2nd test, i got 9/10 right) which mean i need to improve my basic function knowledge. I got the logic, but i lack of fondation knowledge, so all i did was guessing the answer based on the logic. So for the next step i'll find and e-book as reference for the learning path regarding basic excel and also combine it with gemini ai to teach me and summarize all the topic in order to speed up my learning process. 

(https://share.gemini.google/LTPPtSY9L8NX)

To speed up my process, im using notebooklm to summmarize all the resources that i need to learn. I use a book with title of "Beginning Excel 2019 by NOREEN BROWN; BARBARA LAVE; HALLIE PUNCOCHAR; JULIE ROMEY; MARY SCHATZ; ART SCHNEIDER; AND DIANE SHINGLEDECKER" as source of my learning material. On the first 30 minutes i skimmed the first 39 pages just to look up where i need to focuse to learn more. I stopped at page 39 as i found a topic that i've never learn about which 'AutoSum'. So basically autosum is a fuction to help user to do some basic calculation without writes the formula. It can do average, count, sum, min, max, etc. I never use this function before because i used to write the formula manually.

Stared chapter 2 - Mathematical Computations
I decided to jump into real practice by asking gemini ai to create dataset designed spesifically for business problem. The dataset contains transaction id, date, product category, product name, unit cost, selling price, discount per unit, units sold. My task is to calculate the total revenue, total cost, gross profit, and profit margin for each row. It took me 10 minutes to understand and trying to solve it using my own logic. Then i confirmed my answer and my logic with chatgpt, and it told me that i got the logic right, but i need to improve my excel knowledge. I failed to understand the calculation for selling price - discount per unit * Units Sold all substract by Unit Cost * Units Sold which was supposed to be the formula for gross provit. Aside from mathematical skill, i believe that i also need to learn some business language to properly understand the task and give precission answer to solve it.

Basic excel rule [=FunctionName(Arguments)]
Example: =Average(A1:B1), =SUM(A1:B1), etc.

Some Function List:
Function   |   Output   
---------------------------------------------
ABS        |   The absolute value of a number  
AVERAGE    |   The average or arithmetic mean for a group of numbers  COUNT The number of cell locations in a range that contain a numeric value  
COUNTA     |   The number of cell locations in a range that contain text or a numeric value  
MAX        |   The highest numeric value in a group of numbers  
MEDIAN     |   The middle number in a group of numbers (half the numbers in the group are higher than the median and half the numbers in the group are lower than the median)
MIN        |   The lowest numeric value in a group of numbers  
MODE       |   The number that appears most frequently in a group of numbers  
PRODUCT    |   The result of multiplying all the values in a range of cell locations  
SQRT       |   The positive square root of a number  
SUM        |   The total of all numeric values in a group

I skipped several pages because i believe it's irrelevant and too spesific for me to learn right now. It discussed about the implementation of spesific business problem with certain type of function which i believe i can learn it later when i have more time and foundation. 

Chapter 3 - Formulas, Functions, Logical and Lookup Functions 

End of today's session: 2/11/2026 | 04:36 PM
Additional  :   Beginning Excel 2019 page 90