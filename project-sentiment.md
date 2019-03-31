# Sentiment detection

One of the most typical projects that will land on your desk, especially if you work for a .ai or .io company, is sentiment detection of various kinds. So let's try what can be achieved on this front. In this project you will be asked to test building a sentiment detection system.

## Milestone I

There are a number of ready-made English sentiment datasets in the wild. For example [here](https://blog.cambridgespark.com/50-free-machine-learning-datasets-sentiment-analysis-b9388f79c124) are mentioned several, and that is just one of a number of similar lists. Summarize the existing datasets in terms of what is available, and how these datasets differ from each other. Pick two interesting ones from different domains and train a sentiment classifier on them. Report results both in terms of accuracy/precision/recall/F-score on the respective test set, as well as in terms of a small qualitative assessment of the mistakes made by the classifier.

## Milestone II

Expand your previous results with a cross-domain study, in other words train on one dataset, and test on different dataset from a different domain. Report what happens to the results and draw conclusions about the transferability of trained sentiment classifiers across different domains.

## Milestone III

A cool idea of how to build a sentiment analyzer for a target language that has no such tool, e.g. Finnish, would be to machine-translate some English training data to the language of interest and get a sentiment analyzer for free that way - if this idea works, that is. Pick a suitable English dataset and machine-translate it to Finnish or any other foreign language you know, using Google Translate or Bing Translate for example. You can either feed it via the web interfaces or create an account. For example Bing allows a 2M character free quota. Evaluate the resulting sentiment classifier qualitatively as well as quanititatively on a small sample of the target language sentences. You can sample texts from places like Reddit, online shop product reviews, movie reviews, online discussion fora, etc.
