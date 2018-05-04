# MO444A-Assignment-1

## Objective
Explore linear regression alternatives and come up with the best possible model to the problems, avoiding
overfitting. In particular, to predict the number of shares in social networks (popularity).<p>
<p>

## Activities
1. Perform linear regression as the baseline (first solution) and devise LR-based alternative (more
powerful) solutions.<p>
2. Use the specified train/test data for providing your results and avoid overfitting.<p>
3. Devise and test more complex models.<p>
4. Plot the cost function vs. number of iterations in the training set and analyze the model complexity.<p><p>
What are the conclusions? What are the actions after such analyses?<p>
5. Use different Gradient Descent learning rates when optimizing. Compare the GD-based solutions with
Normal Equations if possible (perhaps you should try with smaller sample sizes for this task). What
are the conclusions?<p>
6. Pay attention to the variables that are DISCRETE. You need to take care of them.<p>
7. Prepare a 4-page (max.) report with all your findings. It is UP TO YOU to convince the reader that you
are proficient in the regression subject and the choices related to this particular subject.<p>

## Dataset
Dataset of popularity in Social Nets: https://www.dropbox.com/s/hglzupqi2aubs36/data.zip?dl=0  <p>

## Data Set and Attribute Information:
You should respect the train (80%) / test (20%) splits given.<p>

The dataset was published by Mashable (www.mashable.com) and their content as the rights to reproduce it
belongs to them. Hence, this dataset does not share the original content but some statistics associated with
it. The original content be publicly accessed and retrieved using the provided urls. More info can be found at
the end of this document description.<p>

## Relevant Reading:
K. Fernandes, P. Vinagre and P. Cortez. A Proactive Intelligent Decision Support System for Predicting the
Popularity of Online News. Proceedings of the 17th EPIA 2015 - Portuguese Conference on Artificial
Intelligence, September, Coimbra, Portugal.<p>

## More info on the dataset

Attribute Information:<p>
Number of Attributes: 61 (58 predictive attributes, 2 non-predictive, 1 goal field)<p>

## Attribute Information:
0. url: URL of the article (non-predictive)<p>
1. timedelta: Days between the article publication and the dataset acquisition (non-predictive)<p>
2. n_tokens_title: Number of words in the title<p>
3. n_tokens_content: Number of words in the content<p>
4. n_unique_tokens: Rate of unique words in the content<p>
5. n_non_stop_words: Rate of non-stop words in the content<p>
6. n_non_stop_unique_tokens: Rate of unique non-stop words in the content<p>
7. num_hrefs: Number of links<p>
8. num_self_hrefs: Number of links to other articles published by Mashable<p>
9. num_imgs: Number of images<p>
10. num_videos: Number of videos<p>
11. average_token_length: Average length of the words in the content<p>
12. num_keywords: Number of keywords in the metadata<p>
13. data_channel_is_lifestyle: Is data channel 'Lifestyle'?<p>
14. data_channel_is_entertainment: Is data channel 'Entertainment'?<p>
15. data_channel_is_bus: Is data channel 'Business'?<p>
16. data_channel_is_socmed: Is data channel 'Social Media'?<p>
17. data_channel_is_tech: Is data channel 'Tech'?<p>
18. data_channel_is_world: Is data channel 'World'?<p>
19. kw_min_min: Worst keyword (min. shares)<p>
20. kw_max_min: Worst keyword (max. shares)<p>
21. kw_avg_min: Worst keyword (avg. shares)<p>
22. kw_min_max: Best keyword (min. shares)<p>
23. kw_max_max: Best keyword (max. shares)<p>
24. kw_avg_max: Best keyword (avg. shares)<p>
25. kw_min_avg: Avg. keyword (min. shares)<p>
26. kw_max_avg: Avg. keyword (max. shares)<p>
27. kw_avg_avg: Avg. keyword (avg. shares)<p>
28. self_reference_min_shares: Min. shares of referenced articles in Mashable<p>
29. self_reference_max_shares: Max. shares of referenced articles in Mashable<p>
30. self_reference_avg_sharess: Avg. shares of referenced articles in Mashable<p>
31. weekday_is_monday: Was the article published on a Monday?<p>
32. weekday_is_tuesday: Was the article published on a Tuesday?<p>
33. weekday_is_wednesday: Was the article published on a Wednesday?<p>
34. weekday_is_thursday: Was the article published on a Thursday?<p>
35. weekday_is_friday: Was the article published on a Friday?<p>
36. weekday_is_saturday: Was the article published on a Saturday?<p>
37. weekday_is_sunday: Was the article published on a Sunday?<p>

38. is_weekend: Was the article published on the weekend?<p>
39. LDA_00: Closeness to LDA topic 0<p>
40. LDA_01: Closeness to LDA topic 1<p>
41. LDA_02: Closeness to LDA topic 2<p>
42. LDA_03: Closeness to LDA topic 3<p>
43. LDA_04: Closeness to LDA topic 4<p>
44. global_subjectivity: Text subjectivity<p>
45. global_sentiment_polarity: Text sentiment polarity<p>
46. global_rate_positive_words: Rate of positive words in the content<p>
47. global_rate_negative_words: Rate of negative words in the content<p>
48. rate_positive_words: Rate of positive words among non-neutral tokens<p>
49. rate_negative_words: Rate of negative words among non-neutral tokens<p>
50. avg_positive_polarity: Avg. polarity of positive words<p>
51. min_positive_polarity: Min. polarity of positive words<p>
52. max_positive_polarity: Max. polarity of positive words<p>
53. avg_negative_polarity: Avg. polarity of negative words<p>
54. min_negative_polarity: Min. polarity of negative words<p>
55. max_negative_polarity: Max. polarity of negative words<p>
56. title_subjectivity: Title subjectivity<p>
57. title_sentiment_polarity: Title polarity<p>
58. abs_title_subjectivity: Absolute subjectivity level<p>
59. abs_title_sentiment_polarity: Absolute polarity level<p>
60. shares: Number of shares (target)<p>
 
### => Attribute 60 is your target!
