# Project1-sequence-analysis
A Python program to identify and characterise next-generation sequencing reads with the aim of allowing easier identification of mutation patterns across samples based on treatment.
### How to run the program:
1. Download the file and open it in Colab
2. Upload NGS reads and the reference sequence. The NGS reads should be named reads, and the reference sequence should be named reference 
3. Run all - this is important, as not all functions will work without this
### Inputs: 
This program expects a .csv file containing the reads with columns called read_id, sample, group (containing what the sample was treated with or control) and sequence (containing the NGS read). For the compare_positions function, the names of the control group and treated group must be stated in the input.
### Outputs:
While each function will give you an output, using the final analysis will give you a summary that is easy to interpret. The final analysis will output two tables per group, summarising the reads and mismatches, as well as the substitutions present. It will also list the top positions (up to 3) with mutations.  
### Code design:
In step 4, I created a function to automatically calculate the percentage. I created this so generating percentages was easier and made the code less repetitive.
In step 5, I added round functions to the means and statistics to make the results easier to read and replicate a scientific format. I rounded everything to 2 decimal places except the p-value, which I rounded to 4, since it is often smaller and rounding to only 2 decimal places could lead to false statistical conclusions.
When producing multiple tables from the same code cell, I made sure to include blank print() functions to add clear lines between tables, visually separating them and making them easier to interpret. 
### Testing: 
For step 1, I ran a blank test to ensure the code could cope with empty input without producing value errors. I also ran multiple tests on each function to ensure it could cope with different inputs. I used the assert statement to validate my outputs against the expected outcome
