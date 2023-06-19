# InstaBot
Project Description: Instagram Analysis using Python and Selenium

This project is designed to perform various actions on Instagram using Python and the Selenium library. The objective of the project is to automate tasks such as logging into an Instagram account, searching for profiles, following/unfollowing handles, liking/unliking posts, extracting followers' information, checking stories, analyzing popular handles, scraping post content, finding popular hashtags, calculating followers:likes ratio, and visualizing the collected data.

Here is a breakdown of the project steps:

1. Login to Instagram: The script will automate the login process using a sample username and password.

2. Searching for Handles: The script will type "food" in the search bar and retrieve the names of Instagram handles displayed in the search results, excluding hashtags.

3. Opening a Profile: The script will open the profile of a specific handle, such as "So Delhi."

4. Follow/Unfollow: The script will start following the profile if not already following and display a message accordingly. It will then unfollow the profile and display a message if already unfollowed.

5. Like/Unlike Posts: The script will like the top 30 posts of a specific handle, such as "dilsefoodie," and print a message if a post has already been liked. It will also unlike the previously liked posts and print a message if a post has already been unliked.

6. Extract List of Followers: The script will extract the usernames of the first 500 followers of two handles, "foodtalkindia" and "sodelhi."

7. Analyze Follow/Followers Relationship: The script will compare the followers of "foodtalkindia" that the user is following but who don't follow back. It will print the usernames accordingly.

8. Check Story: The script will check the story of a specific user, "coding.ninjas," and display error messages based on different scenarios: already seen, no story available, or view the story if not seen.

9. Analyzing Habits of Food Bloggers: The script will open the first 10 handles obtained from searching for "food." It will then identify the top 5 handles with the highest number of followers.

10. Number of Posts in the Previous 3 Days: The script will determine the number of posts made by the top 5 handles in the last three days.

11. Graphical Representation: The script will visualize the information collected in the previous step using a suitable graph.

12. Hashtag Analysis: The script will open the 5 handles obtained previously and scrape the content of the first 10 posts of each handle. It will then create a list of words used in the posts and calculate the frequency of each word. The results will be saved in a CSV file.

13. Popular Hashtags: The script will identify the most popular hashtags used by the bloggers and create a pie chart displaying the top 5 hashtags and their frequency.

14. Followers:Likes Ratio: The script will calculate the average followers:likes ratio for the top 5 handles. It will find the likes of the top 10 posts for each handle, calculate the average likes, and divide it by the number of followers to obtain the ratio.

15. Bar Graph: The script will create a bar graph to depict the obtained average followers:likes ratio for each handle.

By performing these steps, the project aims to automate various Instagram actions, collect data, and provide insights into user behavior, popular handles, hashtags, and engagement ratios.
