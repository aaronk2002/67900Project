# 67900Project
The Fall 2022 Machine Learning Project by Aaron, Nguyen, and Rohan

To use the model, you must first download the required files from the following links
1. https://jmcauley.ucsd.edu/data/amazon_v2/categoryFilesSmall/Digital_Music_5.json.gz
2. http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Amazon_Instant_Video_5.json.gz
3. https://nlp.stanford.edu/projects/glove/

For that last one, choose the twitter dataset.

After that, you need to safe these files on a google drive folder named "6.7900 project" and put this folder at your root (My Drive).

The baseline_model.ipynb, dagger_model.ipynb, and loss_model.ipynb can be run once you download those required files, each runs the baseline, dagger, and loss models.
As for the GloVe files, you need to run glove_twitter.ipynb first to get the glove_twitter_25d.pickle file. Then, you need to run glove_embeding.ipynb to get the reviews_amazon_instant_video_twitterglove.npy file. Once finished, you can run the last two files in any order, and these last two are the GloVe and GloVe++ models.
