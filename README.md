# Covid19_analysis

Use Covid19 data uploaded here. Mae your own copy of this data.
First group the total number of cases date wise i.e. (Date{d}, No. of cases on that date{N}).
That is for each date you should have number of New cases on that date stored in Vector N.

Then Find Moving average in this way
A0=0
// For each date calculate moving average in this way
for i in Range(1, Total No. of Dates):
A[i]= Beta*A[i-1] + (1-Beta)N[i]

Now Calculate this for different values of Beta i.e. 0.9, 0.8, 0.7, 0.6, 0.5

Then Plot this moving average with 'date' on X-axis for different values of Beta by giving different colors to different values of beta.
