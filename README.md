# Song-Genre-Prediction-using-Pyspark-mlib
A PySpark MLlib classification model to classify songs based on a number of characteristics into a set of 23 electronic genres. This technology could be used by an application like Pandora to recommend songs to users or just create meaningful channels. Super fun!
## Dataset
Each row is an electronic music song. The dataset contains 100 song for each genre among 23 electronic music genres, they were the top (100) songs of their genres on November 2016. The 71 columns are audio features extracted of a two random minutes sample of the file audio. These features have been extracted using pyAudioAnalysis.

Firstly, I created an algorithm that classifies songs into the 23 genres provided. Then I tested out several different models and select the highest performing one.

## Approach
1] Create Baseline: Train and evaluate models on raw data without pre-treating it for outliers, skewness or negative values. This way we can clearly see what effect our transformations have on our analysis.

2] Test treatments: Train and evaluate models on treated data (outliers, skewness and negative values) and compare to baseline.

3] Parameter Tuning: Select the least performing models from the previous two approaches and add parameters on it to fine tune it.

Finally, Best model is ready for classifiying 23 electronic genres.
