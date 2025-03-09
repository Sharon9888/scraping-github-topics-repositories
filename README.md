# scraping-github-topics-repositories

We are going to scrape https://github.com/topics
We'll get a list of topics. For each topic, we'll get the topic title, topic page URL and topic description
For each topic we'll get the top 25 repositories in the topic from the topic page.
For each repository, we'll grab the repo name, usernames, stars and repo url
For each topic we'll create a CSV file in the following format:

Repo name,User name,Stars,Repo URL
three.js,mrdoob,105000,https://github.com/mrdoob/three.js
react-three-fiber,pmndrs,28000,https://github.com/pmndrs/react-three-fiber
