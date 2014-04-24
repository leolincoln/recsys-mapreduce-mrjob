RecSysMapReduce
===============

For more information, read the blog [post](http://aimotion.blogspot.com/2012/08/introduction-to-recommendations-with.html)

To run this code, you need [mrjob](https://github.com/Yelp/mrjob).

```
python ./movies_count.py data/sampling.csv > output.txt
python ./moviesSimilarities.py data/sampling.csv >output2.txt
```