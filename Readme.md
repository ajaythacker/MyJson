FAKE JSON :
https://my-json-server.typicode.com/ allows you to create a fake mock.
THIS REQUIRES A GITHUB REPO. GITLAB WON'T WORK.

Step 1 : Create a new github repo (I created one with name MyJson)
Pull down the repo
add a db.json file with some json.
example:
{
posts: [
{
id: 1,
title: "Post 1"
},
{
id: 2,
title: "Post 2"
},
{
id: 3,
title: "Post 3"
}
],
comments: [
{
id: 1,
body: "some comment",
postId: 1
},
{
id: 2,
body: "some comment",
postId: 1
},
{
id: 3,
body: "some commentsssssss",
postId: 3
}
],
profile: {
name: "typicode"
}
}

https://github.com/ajaythacker/MyJson

Then you can invoke the endpoint
https://my-json-server.typicode.com/ajaythacker/myjson/posts
where ajaythacker is github account
myjson is the repo
posts is the json inside db.json

