# Forcasting-trending-youtube-content

This project is to develop predictive models that can accurately anticipate which YouTube videos are likely to become trending hits on the platform.This entails analyzing a range of video features to give insights into the aspects that contribute to the popularity and success of a video. By improving content development tactics, viewer engagement, and the overall user experience on YouTube, the initiative aims to empower content producers, advertisers, and viewers. Furthermore, it adds to data analysis, machine learning, and digital marketing research by providing useful insights into developing media trends.
The ability to forecast popular videos may lead to higher viewing, subscription growth, and income generation for content providers and marketers. Market researchers and marketers learn about consumer behavior and preferences in the digital media ecosystem. Our motivation for taking on this project stems from our firm belief that data-driven decision-making may lead to great outcomes in the digital age. By creating predictive models for YouTube video, we hope to help content producers succeed and viewers be satisfied, while also expanding our understanding of how data analytics can be used in digital media platforms.This initiative is in line with our desire to use technology and data to create significant and lasting contributions in the digital domain.

For the project, we used the YouTube Trending Video Dataset from Kaggle. This dataset is a structured and enhanced version of YouTube's own compilation of top-trending videos. It spans multiple regions, including India, the United States, Great Britain, Germany, Canada, France, Russia, Brazil, Mexico, South Korea, and Japan out of which we chose the dataset corresponding to the United States region.  Our original dataset (before pre-processing) consisted of 16 attributes and 236787 data points. The attributes were: video_id,title, publishedAt, channelId, channelTitle, categoryId, trending_date, view_count, description, likes, dislikes, comment_count, tags, thumbnail_link, comments_disabled, ratings_disabled,
The brief description of each attribute is as follows:

video_id: It is a unique identifier for each video.

title: It states the title of the video

publishedAt: The date and time when the video was published.

channelId: Unique identifier for the channel that uploaded the video.

channelTitle: The name of the channel.

categoryId: The category to which the video belongs.

trending_date: The date when the video appeared in the list of trending videos.

tags: Tags associated with the video.

view_count: The number of views the video has received.

likes: The number of likes the video has received.

dislikes: The number of dislikes the video has received.

comment_count: The number of comments on the video.

thumbnail_link: The link to the thumbnail image for the video.

comments_disabled: Boolean value that indicates whether comments are disabled for the video.

ratings_disabled: Boolean value that indicates whether ratings are disabled for the video.

description: The description provided for the video.

Engagement metrics refer to the quantitative measures that assess the level of interaction, participation, and involvement that users have with a particular piece of content or platform. 

In our dataset, the engagement metrics are:

view_count: The number of times the video has been viewed, a key indicator of popularity.

likes: Reflects the positive engagement from viewers.

dislikes: Indicates the level of controversy or disagreement surrounding the video.

 
