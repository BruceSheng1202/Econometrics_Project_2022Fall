# Econmetrics_Project_2022Fall
This is the project detail in the course Econometrics taught by Ying Fang in Xiamen University. In this project, I meticulously studied Professor Hsiao's article titled [A PANEL DATA APPROACH FOR PROGRAM EVALUATION: MEASURING THE BENEFITS OF POLITICAL AND ECONOMIC INTEGRATION OF HONG KONG WITH MAINLAND CHINA](https://onlinelibrary.wiley.com/doi/abs/10.1002/jae.1230) and endeavored to replicate the results using the R programming language. This endeavor, although initially undertaken with a degree of naivety, proved to be a profoundly significant experience that ignited my passion for econometrics and causal inference.

### An Improved Version from DevEcon_Project_2023Spring
In the spring of 2023, I drew inspiration from Hollingsworth's article [Tactics for design and inference in synthetic control studies: An applied example using high-dimensional data](https://osf.io/preprints/socarxiv/fc9xt/) I embarked on a project to adapt the synthetic control method, utilizing ElasticNet penalties and implementing it in R. This innovative approach was motivated by the need to effectively address overfitting and collinearity issues often encountered in high-dimensional time series data analysis.

The motivation for my project stemmed from my perspective that there were certain unfair and unreasonable aspects in prior research. Firstly, I identified a fundamental issue with the first assumption of the Synthetic Control method, which posits that policy treatment should not influence other districts. In the case of using Taiwan as a donor, this assumption is unequivocally violated.

Secondly, I observed a limitation in previous studies, where the donors used were few and confined primarily to the Pacific-Asian region. Given that there might be other countries and regions with characteristics similar to Hong Kong, particularly as a former island colony, I believed that expanding the donor pool for regression analysis could yield more accurate results.

Lastly, I considered the historical context surrounding the project. The announcement declaring the British government's intention to return sovereignty over Hong Kong to China occurred in 1984. Subsequent policy changes in Hong Kong deviated significantly from its prior state. Therefore, I advocated for taking 1984 as the treatment year, as it marked a pivotal juncture in the region's history, making it a more relevant point of reference for the analysis.

In alignment with Hollingsworth's approach outlined in 2022, I conducted a rigorous optimization of parameters through a combination of rolling cross-validation and grid searching. This enhanced methodology have been aplied in another project in my another course, "Issues in Development Economics" taught by Huang Chen at Xiamen University. I am proud to note that the essay I authored, rooted in this methodology, garnered praise from Dr. Chen. It's worth mentioning that the ultimate conclusion drawn from this research aligns with the findings of Hsiao (2012), indicating that the return of Hong Kong to China in 1997 had no statistically significant impact on Hong Kong's GDP.

### Future Improvement
In the upcoming fall of 2023, I am committed to enhancing and refining this project further. 
