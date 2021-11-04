# tiktok_bot

Welcome to tiktok_bot!

This is a project where data is scraped from Tik Tok and is used to train a machine learning model to predict
how much engagement a particular Tik Tok video will get based off of the following metrics: text,
createTime, musicMeta.musicName, musicMeta.musicAuthor, musicMeta.musicOriginal, musicMeta.musicAlbum, musicMeta.duration,
videoMeta.duration, mentions, hashtags.

Currently this project is set up to only use data from the @areyouhappy Tik Tok account. Although this is a small amount
of data for a machine learning model to train on, by modifying the tiktok_scrape.js script's API call and retaining (and utilizing) some of the data associated with the author of a video, this project could be generalize to work for all Tik Tok videos.

In order to run this project you will need to install the tiktok-scraper javascript library, as well as the Naked, pandas, numpy,
scikit-learn, and tensorflow Python libraries.

Use the following commands to install each of these libraries in their respective order:

npm install tiktok-scraper

pip install naked

pip install pandas

pip install numpy

pip install scikit-learn

pip install tensorflow


Once, all of the project's dependencies are satisfied you can run the ttok_bot using the following command from inside the
project'sdirectory:

python3 ttok_bot.py

After the machine learning model is trained and evaluated the results of the model's evaluation will be printed in the console.
