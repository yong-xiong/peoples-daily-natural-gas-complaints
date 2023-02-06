# Where are people complaining natural gas shortages in winter?
As people in the north semiosphere endure the winter, some may not have the heating due to natual gas shortages. Many places in northern China have turned from coal-powered heating to natural gas heating, but due to poor construction quality and natural gas shortages, many people have to live in cold. The project collected data from the [Message Board for Leaders](https://liuyan.people.com.cn/) section of Chinese state media People's Daily. 

## Data source
The data comes from Chinese state media People's Daily website, where hosts [Message Board for Leaders](https://liuyan.people.com.cn/) section and people could post their complaints and suggestions to local governments. Even though local government are not obliged to respond to the complaints or suggestions, because of the publicity of the platform, local governments are likely to at least reply the posts.

By searching keyword "gas shortage" in the section, more than 1,000 posts published after Jan 1, 2022, were available. Using scraping all the posts, the research was able to obtain all the content of these posts, including subjects, the recipients of the complaints which usually contains the geolocation, and the main context of the post. 

## Methodology
The research project collected the publish time via the metadata of the post, and by using [China Province City Area](https://github.com/DQinYuan/chinese_province_city_area_mapper) project, the project was able to obtain the zipcode of the locations and thus the rough coordinations. 

By analyzing the posting time, the project was able to plot a line chart, indicating most of the complaints were sent in mid-to-late December 2022, and complaints decreased significantly in Januray 2023 as it approached the Lunar New Year. 

More than 90% percent of the complaints were "resolved" or at least responded to, by comparing the publishing time and responding time, the project was able to get the average time for local government to reply a post is 21 days, and to get a map showing the average time for each province to address the complaints. 

## Project page
Complaints about natural gas shortage on People's Daily website. Visiting the project [website](https:\\yong-xiong.github.io/peoples-daily-natural-gas-complaints](https://yong-xiong.github.io/peoples-daily-natural-gas-complaints/)).
