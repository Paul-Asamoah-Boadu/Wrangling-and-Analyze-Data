<p align="center">
  <img src="Udacity.png" alt="Udacity logo">
  <br>
  <em>Udacity Data Analyst Nanodegree</em>
</p>

<h1>Project: Wrangle and Analyze WeRateDogs Twitter Archive</h1>
<h2>Table of Content</h2>
<ul>
    <li><a href="#intro">Introduction</a></li>
    <li><a href="#softwares">What Softwares Do I Need?</a></li>
    <li><a href="#motivation">Project Motivation</a></li>
    <li><a href="#details">Project Details</a></li>
      <ul>
            <li><a href="#gathering">Gathering Data</a></li>
            <li><a href="#assessing">Assessing Data</a></li>
            <li><a href="#cleaning">Cleaning Data</a></li>
            <li><a href="#storing">Storing, Analyzing, and Visualizing Data</a></li>
        </ul>
    <li><a href="#report">Report</a></li>
    <li><a href="#reference">References</a></li>
</ul>

<a id="intro"></a>
<h2>Introduction</h2>

Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. You will document your wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.<br><br>


The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "[they're good dogs Brent](https://knowyourmeme.com/memes/theyre-good-dogs-brent)." WeRateDogs has over 4 million followers and has received international media coverage.


WeRateDogs [downloaded their Twitter archive](https://help.twitter.com/en/managing-your-account/how-to-download-your-twitter-archive) and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. More on this soon.
<p align="center">
  <img src="Tweets.png" alt="Image of Tweets" width="800" height="700">
</p>

<a id="softwares"></a>
<h2>What Softwares Do I Need?</h2>

The following softwares and packages (libraries) are required for this project:
- Softwares
  - Jupyter Notebook
  - Microsoft Word
  - [Google Docs](https://www.google.com/docs/about/)
- Packages (Libraries)
  - pandas
  - NumPy
  - matplotlib
  - seaborn
  - requests
  - tweepy
  - json
   
<a id="motivation"></a>
<h2>Project Motivation</h2>

<h3>Context</h3>
My goal for this project is to wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. The Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing and cleaning is required for "Wow!"-worthy analyses and visualizations.<br>
<h3>The Data</h3>

<h4>Enhanced Twitter Archive</h4>

The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which I used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, I have filtered for tweets with ratings only (there are 2356).
<img src="" alt="">



