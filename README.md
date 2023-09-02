# GrowthData
Simple plant treatment growth ANOVA data analysis and bar chart with error bars in python.

Example Output:

![image](https://github.com/KyleBenzle/GrowthData/assets/48848725/ac6989e3-4f2c-4947-9efe-467a26bea3f5)


ANOVA test for Weight
                   sum_sq    df         F    PR(>F)
C(Treatment)    25.615139   2.0  0.300724  0.742289
Residual      1405.439583  33.0       NaN       NaN
P-value: 0.7422889721250909
------------------------------------------------------------
ANOVA test for Root
                   sum_sq    df         F    PR(>F)
C(Treatment)   282.166667   2.0  4.628749  0.016907
Residual      1005.833333  33.0       NaN       NaN
P-value: 0.016907042989067374
Performing Tukey's HSD test for Root as p-value < 0.05
 Multiple Comparison of Means - Tukey HSD, FWER=0.05 
=====================================================
group1 group2 meandiff p-adj   lower    upper  reject
-----------------------------------------------------
     1      2  -6.8333 0.0127 -12.3639 -1.3028   True
     1      3  -2.9167 0.4085  -8.4472  2.6139  False
     2      3   3.9167 0.2066  -1.6139  9.4472  False
-----------------------------------------------------
------------------------------------------------------------
ANOVA test for Meristem
                  sum_sq    df         F    PR(>F)
C(Treatment)  192.666667   2.0  4.792462  0.014885
Residual      663.333333  33.0       NaN       NaN
P-value: 0.014885311955771537
Performing Tukey's HSD test for Meristem as p-value < 0.05
Multiple Comparison of Means - Tukey HSD, FWER=0.05 
====================================================
group1 group2 meandiff p-adj   lower   upper  reject
----------------------------------------------------
     1      2   2.8333 0.2822  -1.658  7.3246  False
     1      3  -2.8333 0.2822 -7.3246   1.658  False
     2      3  -5.6667 0.0108 -10.158 -1.1754   True
----------------------------------------------------
------------------------------------------------------------
ANOVA test for Total_Lng
                  sum_sq    df         F    PR(>F)
C(Treatment)  126.166667   2.0  3.602682  0.038441
Residual      577.833333  33.0       NaN       NaN
P-value: 0.03844092948322258
Performing Tukey's HSD test for Total_Lng as p-value < 0.05
Multiple Comparison of Means - Tukey HSD, FWER=0.05 
====================================================
group1 group2 meandiff p-adj   lower   upper  reject
----------------------------------------------------
     1      2  -2.1667 0.4227 -6.3585  2.0252  False
     1      3  -4.5833 0.0297 -8.7752 -0.3915   True
     2      3  -2.4167 0.3452 -6.6085  1.7752  False
----------------------------------------------------
------------------------------------------------------------
