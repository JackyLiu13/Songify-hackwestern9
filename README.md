# Songify-hackwestern9
<a href="https://docs.google.com/presentation/d/1_4Yy5c729_TXS8N55qw7Bi1yjCicuOIpnx2LxYniTlY/edit?usp=sharing"><h3>Presentation Link</h3></a>
<a href="https://devpost.com/software/hackwesternplaylist"><h2>DevPost</h2></a>

## Inspiration
We all love listening to music on Spotify, but depending on the mood of the day, we want to listen to songs on different themes. Impressed by the cool natural language processing tech that Cohere offers, we decided to create Songify that uses Cohere to create Spotify playlists based on the user's request. 

## What it does
The purpose of Songify is to make the process of discovering new music seamless and hopefully provide our users with some entertainment. The algorithm is not limited in search words so anything that Songify is prompted will generate a playlist whether it be for serious music interest or for laughs.
Songify uses a web based platform to collect user input which Cohere then scans and extracts keywords from. Cohere then sends those keywords to the Spotify API which looks for songs containing the data, creates a new playlist under the user's account and populates the songs into the playlist. Songify will then return a webpage with an embedded playlist where you can examine the songs that were added instantly.

## How we built it
The project revolved around 4 main tasks; Implementing the Spotify API, the Cohere API, creating a webpage and integrating our webpage and backend. Python was the language of choice since it supported the Spotify API, Cohere and Spotipy which extensively saved us time in learning to use Spotify's API. Our team then spent time learning about and executing our specific tasks and came together finally for the integration.

## Challenges we ran into
For most of our team, this was our first time working with Python, APIs and integrating front and back end code. Learning all these skills in the span of 3 days was extremely challenging and time consuming. The first hurdle that we had to overcome was learning to read API documentation. The documentation was very intimidating to look at and understanding the key concepts such as API keys, Authorizations, REST calls was very confusing at first. The learning process included watching countless YouTube videos, asking mentors and sponsors for help and hours of trial and error.

## Accomplishments that we're proud of
Although our project is not the most flashy, our team has a lot to be proud of. Creating a product with the limited knowledge we had and building an understanding of Python, APIs, integration and front end development in a tight time frame is an accomplishment to be celebrated. Our goal for this hackathon was to make a tangible product and we succeeded in that regard.

## What we learned
Working with Spotify's API provided a lot of insight on how companies store data and work with data. Through Songify, we learned that most Spotify information is stored in JSON objects spanning several hundred lines per song and several thousands for albums. Understanding the Authentication process was also a headache since it had many key details such as client ids, API keys, redirect addresses and scopes.
Flask was very challenging to tackle, since it was our first time dealing with virtual environments, extensive use of windows command prompt and new notations such as @app.route. Integrating Flask with our HTML skeleton and back end Python files was also difficult due to our limited knowledge in integration.
Hack Western was a very enriching experience for our team, exposing us to technologies we may not have encountered if not for this opportunity.

## What's next for HackWesternPlaylist
In the future, we hope to implement a search algorithm not only for names, but for artists, artist genres, and the ability to scrub other people's playlists that the user enjoys listening to. The appearance of our product is also suboptimal and cleaning up the front end of the site will make it more appealing to users. We believe that Songify has a lot of flexibility in terms of what it can grow into in the future and are excited to work on it in the future.
