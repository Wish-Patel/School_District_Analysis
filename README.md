# School_District_Analysis

Performance based analysis of different hgihschools in a schoold district using python and pandas library.

The analysis is comprised of the specific school data focusing on size, funding and district type. Along with student data focused on reading and math scores for grades 9 to 12. 
Using Python and the Pandas library, it was determined that schools with under $585 of budget per student and sized between 1-2K students tend to have a higher over all passing percentage.
However, it was later determined the data was skewed due to an unfortunate academic dishonesty reporting for grade 9 students at Thomas High School. After assessing the situation it was then determined to remove the scores for all grade 9 students for Thomas High and perform the analysis again.

Below are the results of the affects of this discrepency.

Looking at the broad picture at a district level, there is a slight drop in the scores and passing averages.

With grade 9 Thomas High scores:
![District_summary](https://github.com/Wish-Patel/School_District_Analysis/blob/master/With_Thomas_9ers/District_summary.PNG)

Without grade 9 Thomas High scores:
![District_summary](https://github.com/Wish-Patel/School_District_Analysis/blob/master/Without_Thomas_9ers/District_summary.PNG)


However once we start drilling down at the school level, removing the grade 9 scores from Thomas high had a significant impact on the over all ranking of the school as it goes from being a top 3 performing schools to the last in the district.

With grade 9 Thomas High scores:
![School_scores](https://github.com/Wish-Patel/School_District_Analysis/blob/master/With_Thomas_9ers/School_scores.PNG)

Without grade 9 Thomas High scores:
![School_scores](https://github.com/Wish-Patel/School_District_Analysis/blob/master/Without_Thomas_9ers/School_scores.PNG)


We can see this by taking a look at the math and reading scores for each highschool at the grade level. The contributing factor is the null value for the grade 9 math and reading scores for Thomas High.

With grade 9 Thomas High math and reading scores:

![Math_scores](https://github.com/Wish-Patel/School_District_Analysis/blob/master/With_Thomas_9ers/Math_scores.PNG)  ![Reading_scores](https://github.com/Wish-Patel/School_District_Analysis/blob/master/With_Thomas_9ers/Reading_scores.PNG)

Without grade 9 Thomas High math and reading scores:

![Math_scores](https://github.com/Wish-Patel/School_District_Analysis/blob/master/Without_Thomas_9ers/Math_scores.PNG)  ![Reading_scores](https://github.com/Wish-Patel/School_District_Analysis/blob/master/Without_Thomas_9ers/Reading_scores.PNG)


Schools with a spending range of $630-644 saw a 7% drop in the overall passing percentage, brining them to the last place.

With grade 9 Thomas High scores:
![Spending_scores](https://github.com/Wish-Patel/School_District_Analysis/blob/master/With_Thomas_9ers/Spending_scores.PNG)

Without grade 9 Thomas High scores:
![Spending_scores](https://github.com/Wish-Patel/School_District_Analysis/blob/master/Without_Thomas_9ers/Spending_scores.PNG)


Medium sized schools went from tying for first place with small size schools to second place. Still significantly performing better than the larger school size.

With grade 9 Thomas High scores:
![SchoolSize_scores](https://github.com/Wish-Patel/School_District_Analysis/blob/master/With_Thomas_9ers/SchoolSize_scores.PNG)

Without grade 9 Thomas High scores:
![SchoolSize_scores](https://github.com/Wish-Patel/School_District_Analysis/blob/master/Without_Thomas_9ers/SchoolSize_scores.PNG)


Lastly, while charter type schools still have a significantly better performance than district type schools, the overall passing percentage did drop by 4%.

With grade 9 Thomas High scores:
![SchoolType_scores](https://github.com/Wish-Patel/School_District_Analysis/blob/master/With_Thomas_9ers/SchoolType_scores.PNG)

Without grade 9 Thomas High scores:
![SchoolType_scores](https://github.com/Wish-Patel/School_District_Analysis/blob/master/Without_Thomas_9ers/SchoolType_scores.PNG)
