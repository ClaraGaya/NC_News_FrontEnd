# Northcoders News

A Reddit clone built in Mongo, Express, React, Redux and Bulma.

---

## Instructions
After cloning this repo please take the following steps.
1. Open a terminal.
2. In the terminal, run `npm install`.
3. After install is complete then type into the terminal, `npm run start`.
6. The front-end is now accessible on port 9090.

---
## Northcoders News Front-End

Northcoders News is a social news aggregation, web content rating, and discussion website. It is similar to [Reddit](https://www.reddit.com/)

Northcoders News has articles which are divided into topics. Each article has user curated ratings and can be up or down voted using the API.
Users can also add comments about an article. Comments can also be up or down voted. A user can add comments and remove any comments which
they have added.

### Objectives
1. Pull together all the skills and technologies you have learnt over the past three weeks.
2. Learn about working with a [C.R.U.D](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete) application from a front end perspective.
3. Make more advanced asynchronous API calls.
4. Begin to familiarise yourself with the various HTTP response codes and update your UI accordingly.
5. Learn more common HTTP request types `POST`, `PUT` & `DELETE`
6. Learn more about interacting with a server using URL queries and request bodies.

You will be getting the data from your implementation of the Northcoders News API server.

### Stages

1. Have a look at your API endpoints and at Reddit. Think about what data you have available, and how you will structure your application. What routes will your application have? What articles will you choose to display on the main page?

2. Set up your routing with React Router. Render dummy components and make sure they are rendering in the right place.

3. Think about what data each component will need. Where will it come from? Will any components need to pass data down to dumb components as props? Focus on loading a list of articles for your front page first of all.

4. Consider more complex functionality. You should be able to post a new comment on a topic. NB all comments you post from your app will automatically have the username 'northcoder'. Consider whether the comments will appear in order of popularity or by time.

5. You should also be able to delete comments that you have posted. If you try to delete a comment that does not have the author 'northcoder' the API throws an error.

6. Each comment, and each article, can be upvoted or downvoted. See the [API reference](https://northcoders-news-api.herokuapp.com/) which explains how to to this.

### Users

Users are available from the API and have already been busy adding comments to the articles! There is also a 'northcoder' user. Any comments you add will belong to the 'northcoder' user and you will also be able to delete those comments using the API.

