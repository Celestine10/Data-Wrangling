# Data-Wrangling
## Qualitative-Data
Qualitative data refers to non-numeric information such as interview transcripts, notes, video and audio recordings, images and text documents. <br>

Qualitative data analysis is a process of gathering, structuring and interpreting qualitative data to understand what it represents.

Qualitative data is non-numerical and unstructured. This could be text, such as open-ended responses to survey questions or user interviews, but it also includes audio, photos and video.

Most qualitative dataset are more of a hoizontal format rather than vertical. Unfortunately, computers are much better at handling data of significant length rather than significant width compared to humans who prefer to read across rather than read up and down.

In this project, I utilized the power Excel and Python to transpose, rearrange and analyse this interview dataset from a wider format into a usable format. It was  gotten from an interview that was conducted with Survey Monkey and contains two header rows . 

The major steps that was used in carrying out this analysis are as follows:

1. Save the original dataset in order to have the old format in case of any errors.
2. Create a new sheet named Question
3. Copy the Question row and paste it (Use Paste transpose) on the new sheet created in step 2 above.
4. Copy the subquestion row an paste it (Use Paste transpose) on another column, on the new sheet created in step 2 above. 
Both columns are named question and subquestion respectively.
5. **Use an IF function to fill up blank spaces -**  If a cell is blank, use the cell above it to fill it up (for both columns).
6. Create a new column called Question + subquestion and Concatenate theem using the concat function.
7. Create a new sheet called Data_Edited (can be any name), copy the values from the original data sheet and paste it there.

I then imported the file into a jupyter notebook using python's pandas data analysis library. With pandas, 
I was able to perform some feature engineering on the data to answer the following questions: <br>

**- How many people responded to the questions.** <br>

**- How many answers were given to these questions.**

**- How many people gave the same answer per question**
