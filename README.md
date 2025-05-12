# Netflix_EDA
NETFLIX MOVIES AND TV SHOWS CLUSTERING

** Project Summary -
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service's number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

** About your dataset?

* The dataset includes movies and TV shows available on Netflix as of 2019.
* It contains **multiple missing values**, particularly in columns such as `director`, `cast`, `country`, `rating`, and `date_added`.
* A few **duplicate rows** may exist, and if so, should be considered for removal to prevent bias in analysis.
* The data types are mostly `object` (categorical), but some columns like `release_year` and `duration` can be converted for numerical or time-series analysis.
* Features such as `listed_in` (genre) are multi-valued and will need preprocessing (like splitting or exploding).
* The dataset is a rich source for performing **UBM analysis** to derive content trends and viewer-targeting strategies.


** Problem Statement - 
The global entertainment industry has undergone a massive transformation with the rise of Over-The-Top (OTT) platforms, and Netflix stands at the forefront of this digital revolution. With an expansive and ever-growing library of TV shows and movies available across various countries and genres, Netflix is constantly challenged to curate, categorize, and recommend content effectively to retain users, maximize engagement, and ensure long-term subscriber growth.
This project aims to perform a detailed Exploratory Data Analysis (EDA) on a dataset that consists of TV shows and movies available on Netflix as of 2019. The dataset, collected from Flixable—a third-party Netflix search engine—includes features such as show type, title, director, cast, country, date added, release year, rating, duration, and genre.

** Objectives -

To understand the composition and distribution of content available on Netflix across various dimensions like content type, duration, genre, release year, and country of origin.
To identify patterns and trends in Netflix's content acquisition strategy over time.
To analyze seasonal behaviors—such as which months see more content additions.
To explore content diversity and the dominance of specific genres, countries, or ratings.
To apply clustering techniques to identify groups of similar content based on duration and release year, which could potentially assist in recommendation systems or personalized content delivery.
To uncover actionable business insights that Netflix could leverage to improve its content strategy, localization, user experience, and market segmentation.
Business Need:

Netflix constantly aims to enhance viewer satisfaction and retention. This requires a deep understanding of how its content library is structured and evolving. By identifying viewing patterns, content gaps, over-represented areas, and audience targeting opportunities.
Through structured EDA and clustering, this project not only explores Netflix's content landscape but also provides actionable insights that align with business objectives.

* Conclusion -
* The exploratory data analysis of the Netflix dataset has provided valuable insights into the platform's content library.
* We observed the distribution of content types, ratings, release years, and the trends in content addition over time.
* The analysis of genres revealed popular categories and their associated ratings, offering a glimpse into audience preferences.
* Furthermore, examining the relationship between duration and other variables helps understand the typical length of different content types and ratings.

# Key findings include:
- Movies constitute a larger portion of the content compared to TV shows.
- A significant amount of content is rated for mature audiences.
- Content addition has seen a substantial increase in recent years.
- Genres like 'Dramas', 'Comedies', and 'International Movies' are prevalent.
- Certain genres are strongly associated with specific age-based ratings.

# These insights can inform strategic decisions for Netflix, such as:
- Optimizing content acquisition and production to balance the content library and cater to diverse audience preferences.
- Tailoring marketing efforts towards specific demographics based on genre and rating popularity.
- Enhancing content recommendation systems by considering genre and rating distributions.
- Refining parental control features to ensure age-appropriate content access.

# Further analysis could involve clustering and machine learning techniques to segment content and predict viewer behavior.
# Additionally, time series analysis on content addition trends could provide forecasts for future growth and help in resource planning.


