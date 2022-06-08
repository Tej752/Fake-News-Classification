# Fake-News-Classification
Classification of Fake and Real News


A type of yellow journalism, fake news encapsulates pieces of news that may be hoaxes and is generally spread through social media and other online media. This is often done to further or impose certain ideas and is often achieved with political agendas. Such news items may contain false and/or exaggerated claims, and may end up being viralized by algorithms, and users may end up in a filter bubble.


![image](https://user-images.githubusercontent.com/65494424/172558491-fbc3d453-e471-4b53-9f95-94ae23ea013a.png)



There are methods that can be used in the Natural Language Processing toolbox that can be used to preprocess our text: Count Vectorization and Term Frequency-Inverse Document Frequency.

Count Vectorization involves counting the number of occurrences each words appears in a document

If you want to play around with CountVectorizer, you can fiddle with three parameters. First of them is max_df. This pretty much sets how many features, or in this case words, you want CountVectorizer to count. Setting this parameter can be incredibly useful when dealing with a large amount of documents as you’ll run into speed issues with computation.

Another is ngram_range. This deals with contiguous sequences of words. Let’s say you want to deal with features such as “peanut butter and jelly”, “intercontinental flight”, or “rush hour traffic”, you can get a lot more meaning than if you put all of these words as independent features. You could lose the meaning if you don’t set this parameter.
