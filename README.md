# YouTube Data Analysis Project

In this project, I'm delving into YouTube's wealth of data using the YouTube API. My goal? To extract, arrange, and dissect valuable information. Using Python Pandas, I'll transform this data into a potent analytical resource. As we journey forward, I'll enhance understanding through visuals created with the Python Seaborn library.


## Essential Links

- Create a YouTube API Key: [Get Yours](https://console.cloud.google.com/)
- YouTube Data API Documentation: [Explore](https://developers.google.com/youtube/v3)

## Accessing Channel Statistics

*Function: get_channel_stats()*

My journey kicks off with building a custom function, get_channel_stats(). This handy tool is my backstage pass to the YouTube API. With it, I can tap into the stats of multiple YouTube channels. It's like having a golden key to unlock valuable insights like channel names, subscriber counts, total views, and video upload counts.

## Data Preprocessing

Now that I have a treasure chest of channel stats, I pivot to the crucial data preprocessing phase. Here, I precisely structure and organize my data using Pandas. This step lays the foundation for deep analysis. 

## Data Visualization

In this section, I wield the Seaborn library as my creative brush. I craft some visualizations that transform raw numbers into compelling insights. These visuals make it a breeze to compare subscriber counts, total views, and video quantities across the YouTube channels I'm exploring.

## Extracting Video Details

*Function: get_video_ids()*

Now, I roll up my sleeves and dive into the complicated world of video data. My custom function, get_video_ids(), takes the spotlight. It helps me pluck video IDs from specific channel upload playlists using the YouTube API. This step is like finding the key to unlock secrets about each video.

*Function: get_video_details()*

Once I have a special list of video IDs, I start to explore and learn all about the videos. This includes key elements like video titles, publication dates, view counts, likes, and comments. This phase reveals the essence of the content within these YouTube channels.

## Video Data Analysis

Armed with comprehensive video details, I flawlessly assemble them into a Pandas DataFrame. This crucial phase focuses on data preprocessing to ensure my dataset is primed for analysis.

## Top 10 Videos by Views

In this exciting chapter, I unveil the top 10 videos by views. Through a well-crafted bar plot, I showcase the charm of these top-performing videos, offering a glimpse into what captivates the audience.

## Videos Published Over Time

Understanding the rhythm of content release within these channels is essential. I dive into the distribution of video releases across months, observing the frequency of content publication.

## Data Export

As our journey reaches its conclusion, I export my  collected and analyzed video data to a CSV file. This step ensures that my hard work can be further explored, or shared, adding depth to the understanding of the YouTube channels under my examination.
