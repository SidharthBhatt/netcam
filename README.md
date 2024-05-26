## Inspiration

When the COVID-19 pandemic hit, people across the world suddenly began to spend an unprecedented amount of time online partaking in niche communities. As travel became less frequent, anxiety and loneliness increased by 25.3% (UNC Chapel Hill). Also, due to the advent of short-form video platforms like TikTok, there was a significant decrease in attention span and working memory (Forbes-Statista).

Additionally, platforms such as Google Earth and Street View are notably popular among people who want but are unable to explore the world, and organizations like zoos and museums have an interest in hosting live streams of their little corner of the world.

However, there isn’t a cohesive, extensive site that combines all of these elements — which is where NetCam comes in. 

## What it does

NetCam is a social media and entertainment platform that allows people to view cameras from around the globe, and also to create and register their own livestreams. NetCam’s wide database of locations range from famous landmarks to small side-streets, and can be easily added to by users themselves. Furthermore, users will be able to vote on livestreams, access recommendations, and share their favorite cameras with others. This fosters an increasingly interconnected world with an appreciation for the smaller things in life. 

## How we built it

This web app was built primarily using React.js, along with HTML and CSS. The backend was developed with Java and Selenium webdrivers, Python for webscraping automation, and Pandas for csv-data parsing and analysis. The hardware portion is powered by a Raspberry Pi and a webcam. It uses OpenCV to capture video and ngrok is used to make it a livestream. 

## Challenges we ran into

- The 3D textures were something our team hasn’t used before, so it took some trial and error before we got it down.
- The Raspberry Pi was a little finicky at first.
- The automation of the webscraping required a lot of challenging finetuning.
- Soooo many divs to size and center…
- We were having so much fun that we forgot to eat dinner!

## Accomplishments that we're proud of

We’re especially proud of the interactive and rotatable model Earth on our homepage, with an attractive and realistic UI to go along with it.

## What we learned

Some members learned the basics of front-end design with React.js. We also revisited and revitalized existing skills relating to webscraping, learning about Selenium and WebDrivers.

## What's next for NetCam

We can’t wait to introduce even more cameras that provide unique views of the world. We also want to improve the social media aspect of our product, allowing people to follow certain users, save cams, comment, and so on. We would also like increased support for different languages, allowing even more people to use our product easily. Finally, we would also like to integrate the remote control of cameras instead of static view through a feed. 