# web-bot-navigator-downloader
<b>Motivation: </b>As a member of seanwilsonpiano.com _(a piano tutoring site)_, I paid a monthly subscription fee of $30 for video lessons which I didn't have enough time to watch and learn from. The website _does NOT_ offer the possibility to download the videos. So I decided to cancel the subscription, but before I did so, I used selenium and vimeo-downloader to write a web bot that will downloaded all video lessons from specific sections of the website to my computer. This python notebook is a tutorial on how you can use Selenium for similar web automated tasks<br><br>
A web bot using Selenium to log in to a website, access over 100 webpages and retrieve content (videos and URLs). The bot will navigate to all the webpages, interact with various html elements on the website to retrieve video URLs, which we'll download using vimeo-downloader. Programmatically organize the downloaded files/videos in different folders on disk.
Using Selenium, a Chrome WebDriver, and vimeo-downloader I'll:
- Log in to seanwilsonpiano.com (where I was a member)
- navigate to video lessons and obtain the video URLs
- save URLs as JSON on file
- download all videos and organize them on the file system
