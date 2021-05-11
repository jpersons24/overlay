# Overlay

Overlay is a web application built using a *React with Hooks* front end and a *Ruby on Rails* back end. Designed as an application for sports fans to see upcoming events, latest news headlines and updated betting odds for specific games. Overlay provides a forum for users to share thoughts, opinions and insights with other users about games, teams and odds that are presented.

In terms of gambling, the term *overlay* is used to describe odds which favor the player rather than the house.

## Description

A user of Overlay will be able to get see the latest sports headlines, automatically updated throughout the day. Users can 'favorite' news articles to save for later reading and remove them from their favorites list once they have read them. Links are also provided to the article's source page.

News stories are fetched using the RESTful [News API](https://newsapi.org/).

Users will also be able to see upcoming events. Presented with a Carousel feature from 'React Bootstrap'. Each game will have both teams, event time and the most up to date betting odds from various odds makers!

Event and odds information fetched using the RESTful [odds-api](https://the-odds-api.com/)

Finally, Overlay has been designed to give users and sports fans a place to communicate with others about their favorite teams, opposition teams and odds that are being placed on specific games. Through a 'post' type format, a User can leave insight they may have on injuries or team news that may affect the way bets are placed or odds viewed.


> Overlay is still in development. Plans for further features, additional content and design/brand development are in the works currently. A more detailed road map will be provided as time allows.

## Installation

1. Start by cloning the overall project repository.
2. Change directories `cd overlay-frontend` into the front end react application. Assuming that you have used NPM before, run the command `npm install` from your command line. Once NPM installation has completed, run the command `npm start` to start the server and the application will open automatically in your browser window.
3. Next, cd back to the top level directory and `cd overlay-backend` into the back end directory. Once in that directory run `rails s -p 4000` to start the back end server.
4. Once both servers are up and running, in your internet broswer all you have to do is sign into your user account, or create one if you have yet to do so. Once logged in, you will be able to navigate around the site as your wish!



If you have questions, concerns or any issues please send an email to jakob.e.persons@gmail.com with breif but detailed description of the issue. It will be addressed as soon as possible.