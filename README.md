# The Ultimate Food Finder

The Ultimate Food Finder is an app that helps you find dishes that are not only good for your health but also delicious and easy to make by your standards. See full proposal here: https://github.com/cstorm125/food/blob/master/proposal.ipynb

We sift through over 240,000 recipes on allrecipes.com to bring you the right recipe based on nutritional facts, quantity and complexity of instructions, time taken to prepare the dish, prevalence of ingredients, ratings and reviews of the recipe and from user accounts. As a proof of concept, we successfully scraped about 1% of the dataset and created plots showing tradeoffs between conveience and nutritional values as well as deliciousness. 

Figure 1 is a scatterplot of recipies with highest vitamins as percentage of daily intake on one axis and time used to prepare and cook the meal on the other. We also did a clustering on the recipes to determine groups of similar dishes. This allows us to choose to make the group of dishes that take less time and are more healthy.

![Figure 1](https://github.com/cstorm125/food/blob/master/figure1.png?raw=true)

Figure 2 is another scatterplot of recipies with ratings on one axis and number of ingredients on the other (each ingredient is weighted using inverse document frequency to give more weights to rare ingredients). We can look at this plot and choose the dish that is delicious (by popular demands) and easy to make.

![Figure 2](https://github.com/cstorm125/food/blob/master/figure2.png?raw=true)

For the 8-week capstone, we can develop more nuanced metrics that represent the three pillars of this proposal: convenience, health, taste. Instead of just time to finish and ingredient availability, we can add localization of ingredients (scraping more datasets), ease of substitution (graph analysis), instruction complexity (text mining). For nutritions, we can find a more objective and academically rigorous representations of a healthy meal, and plan not just for one meal but for the day or even week. And instead of overall popularity as deliciousness, we can build a recommendation engine for each person based on user reviews (collaborative filtering).

Past works done with similar datasets include simple exploration (Kimmel, 2016), recipe similarity (Hunt, 2004), recipe recommendation based on ingredient networks (Teng et al, 2012), and recipe generation (Ahn et al, 2011; Varshney et al, 2013). This proposal, to the best of our knowledge, is novel in its approach of combining nutritional benefits with prefrences and convenience.

References
- Ahn, Y., Ahnert, S. E., Bagrow, J. P., & Barabási, A. (2011). Flavor network and the principles of food pairing. Scientific Reports, 1(1). doi:10.1038/srep00196
- Hunt, T. D. (2004). U.S. Patent No. US7299245B2. Washington, DC: U.S. Patent and Trademark Office.
- Kimmel, Y. (2016). All the recipes: Scraping the top 20 recipes of allrecipes. Retrieved from https://nycdatascience.com/blog/student-works/recipes-scraping-top-20-recipes-allrecipes/
- Overweight & Obesity. (2018, June 12). Retrieved from https://www.cdc.gov/obesity/data/adult.html
- Pew Research Center (2006). Eating More; Enjoying Less. Retrieved from http://www.pewsocialtrends.org/2006/04/19/eating-more-enjoying-less/
- Teng, C., Lin, Y., & Adamic, L. A. (2012). Recipe recommendation using ingredient networks. Retrieved from https://arxiv.org/abs/1111.3919.
- Varshney, L. R., Pinel, F., Varshney, K. R., Bhattacharjya, D., Schoergendorfer, A., & Chee, Y. (2013). A Big Data Approach to Computational Creativity. Retrieved from https://arxiv.org/abs/1311.1213.
