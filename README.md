# get-youtube-subs
This is backend Capstone project of getYouTube subscribers—

To create getYouTube subscribers application i used–

1-Node.js

2-Express.js

3-MongoDB

4-Mongoose


This getYouTube subscribers application provides an API to get details of YouTube subscribers.

Routes :-

1-GET/subscribers - Response with an array of subscribers(an object).

2-GET/subscribers/names - Response with an array of subscribers(an object with only two fields name and subscribedChannel).

3-GET/subscribers/:id - Response with a subscriber(an object) with given id response with status code 400 and Error message ({message:error.message}) if id
does not match.
