# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200

https://cat-fact.herokuapp.com/facts


1. 301
1. 400
1. 401
https://www.movebank.org/movebank/service/direct-read?entity_type=study


1. 403

http://finance.google.com/finance/info?client=ig&q=NASDAQ%3AAAPL,GOOG

1. 404
https://cat-fact.herokuapp.com/factst


1. 418
https://httpstatuses.com/418

1. 500
https://www.booknomads.com/dev


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat


# Part Two

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact
```swift

https://cat-fact.herokuapp.com/facts

"all": [
{
"_id": "5887e1d85c873e0011036889",
"text": "Cats make about 100 different sounds. Dogs make only about 10.",
"type": "cat",
"upvotes": 9,
"userUpvoted": null
},
{
"_id": "58e0086f0aac31001185ed02",
"text": "Cats can't taste sweetness.",
"type": "cat",
"user": {
"_id": "58e007480aac31001185ecef",
"name": {
"first": "Kasimir",
"last": "Schulz"
}
},
"upvotes": 8,
"userUpvoted": null
},
{
"_id": "591d9bb2227c1a0020d26826",
"text": "The CIA spent US$20 million in the 60s training cats to spy on the Soviets. The first spy cat was hit by a taxi.",
"type": "cat",
"user": {
"_id": "587288f6e6f85e64ae1c7ef7",
"name": {
"first": "Alex",
"last": "Wohlbruck"
}
},
"upvotes": 8,
"userUpvoted": null
},
{
"_id": "588e746706ac2b00110e59ff",
"text": "Domestic cats spend about 70 percent of the day sleeping. And 15 percent of the day grooming.",
"type": "cat",
"user": {
"_id": "588e6e8806ac2b00110e59c3",
"name": {
"first": "Thomas",
"last": "Lockwood"
}
},
"upvotes": 8,
"userUpvoted": null
},
{
"_id": "5b1b40d4841d9700146158d8",
"text": "Koko the gorilla got a pet cat for her birthday in 1985 after she requested to have one as a birthday present.",
"type": "cat",
"user": {
"_id": "5a9ac18c7478810ea6c06381",
"name": {
"first": "Alex",
"last": "Wohlbruck"
}
},
"upvotes": 8,
"userUpvoted": null
},
{
"_id": "58e009420aac31001185ed11",
"text": "Basically all cartoon cats lied to us: Raw fish is off the table for cats as well.",
"type": "cat",
"user": {
"_id": "58e007480aac31001185ecef",
"name": {
"first": "Kasimir",
"last": "Schulz"
}
},
"upvotes": 7,
"userUpvoted": null
},
{
"_id": "58e007f50aac31001185ecf8",
"text": "A group of cats is called a clowder.",
"type": "cat",
"user": {
"_id": "58e007480aac31001185ecef",
"name": {
"first": "Kasimir",
"last": "Schulz"
}
},
"upvotes": 7,
"userUpvoted": null
},
{
"_id": "5b4910ae0508220014ccfe90",
"text": "Cats can hear the ultrasonic noises that rodents and dolphins make to communicate.",
"type": "cat",
"user": {
"_id": "5a9ac18c7478810ea6c06381",
"name": {
"first": "Alex",
"last": "Wohlbruck"
}
},
"upvotes": 7,
"userUpvoted": null
},
{
"_id": "58e00af60aac31001185ed1d",
"text": "It was illegal to slay cats in ancient Egypt, in large part because they provided the great service of controlling the rat population.",
"type": "cat",
"user": {
"_id": "58e007480aac31001185ecef",
"name": {
"first": "Kasimir",
"last": "Schulz"
}
},
"upvotes": 7,
"userUpvoted": null
},
{
"_id": "5894af975cdc7400113ef7f9",
"text": "The technical term for a cat’s hairball is a bezoar.",
"type": "cat",
"user": {
"_id": "587288f6e6f85e64ae1c7ef7",
"name": {
"first": "Alex",
"last": "Wohlbruck"
}
},
"upvotes": 6,
"userUpvoted": null
},
{
"_id": "58e0088b0aac31001185ed09",
"text": "The world's largest cat measured 48.5 inches long.",
"type": "cat",
"user": {
"_id": "58e007480aac31001185ecef",
"name": {
"first": "Kasimir",
"last": "Schulz"
}
},
"upvotes": 6,
"userUpvoted": null
},
{
"_id": "5b0c5e3e7ab3c50014df65fe",
"text": "People who own cats have on average 2.1 pets per household, where dog owners have about 1.6.",
"type": "cat",
"user": {
"_id": "5a9ac18c7478810ea6c06381",
"name": {
"first": "Alex",
"last": "Wohlbruck"
}
},
"upvotes": 6,
"userUpvoted": null
},
{
"_id": "58e009550aac31001185ed12",
"text": "The oldest cat video on YouTube dates back to 1894.",
"type": "cat",
"user": {
"_id": "58e007480aac31001185ecef",
"name": {
"first": "Kasimir",
"last": "Schulz"
}
},
"upvotes": 6,
"userUpvoted": null
},
{
"_id": "58e00a000aac31001185ed15",
"text": "Female cats are typically right-pawed while male cats are typically left-pawed.",
"type": "cat",
"user": {
"_id": "58e007480aac31001185ecef",
"name": {
"first": "Kasimir",
"last": "Schulz"
}
},
"upvotes": 6,
"userUpvoted": null
},
{
"_id": "58e00a1a0aac31001185ed18",
"text": "Cats and humans have nearly identical sections of the brain that control emotion.",
"type": "cat",
"user": {
"_id": "58e007480aac31001185ecef",
"name": {
"first": "Kasimir",
"last": "Schulz"
}
},
"upvotes": 6,
"userUpvoted": null
```
```swift

1. A list of 150 random users in English.

https://opencollective.com/webpack/members/organizations.json

"MemberId": 42412,
"createdAt": "2019-06-08 00:04",
"type": "ORGANIZATION",
"role": "BACKER",
"tier": "Backer",
"isActive": false,
"totalAmountDonated": 3737,
"lastTransactionAt": "2019-08-26 19:21",
"lastTransactionAmount": 0,
"profile": "https://opencollective.com/triplebyte",
"name": "Triplebyte",
"company": null,
"description": "Triplebyte is the first software engineering job platform that is on the developer's side. Take our coding quiz!",
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/02f87560-b2f1-11e8-85a0-75f200a0e2db.png",
"email": null,
"twitter": "https://twitter.com/triple_byte",
"github": null,
"website": "https://triplebyte.com/os/opencollective"
},
{
"MemberId": 43333,
"createdAt": "2019-06-18 14:54",
"type": "ORGANIZATION",
"role": "BACKER",
"isActive": true,
"totalAmountDonated": 3737,
"lastTransactionAt": "2019-08-26 19:21",
"lastTransactionAmount": 0,
"profile": "https://opencollective.com/triplebyte",
"name": "Triplebyte",
"company": null,
"description": "Triplebyte is the first software engineering job platform that is on the developer's side. Take our coding quiz!",
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/02f87560-b2f1-11e8-85a0-75f200a0e2db.png",
"email": null,
"twitter": "https://twitter.com/triple_byte",
"github": null,
"website": "https://triplebyte.com/os/opencollective"
},
{
"MemberId": 2258,
"createdAt": "2016-11-23 11:42",
"type": "ORGANIZATION",
"role": "BACKER",
"isActive": true,
"totalAmountDonated": 4522,
"currency": "USD",
"lastTransactionAt": "2017-09-23 12:43",
"lastTransactionAmount": 2,
"profile": "https://opencollective.com/tipe",
"name": "Tipe",
"company": null,
"description": "Generate an API-first CMS from a GraphQL schema with offline prototyping and an inline editor",
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/58581ee0-e4f5-11e7-9265-3f31ae7252f5.png",
"email": null,
"twitter": "https://twitter.com/TipeIO",
"github": null,
"website": "https://tipe.io?ref=opencollective"
},
{
"MemberId": 2491,
"createdAt": "2016-12-13 19:49",
"type": "ORGANIZATION",
"role": "BACKER",
"isActive": true,
"totalAmountDonated": 12000,
"currency": "USD",
"lastTransactionAt": "2016-12-14 18:56",
"lastTransactionAmount": 6000,
"profile": "https://opencollective.com/capitalone",
"name": "Capital One",
"company": null,
"description": null,
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/2015_Capital_One_Logopng_87cc0240-c174-11e6-8db6-7b1babac25cc.png",
"email": null,
"twitter": "https://twitter.com/capitalone",
"github": null,
"website": "https://www.capitalone.com"
},
{
"MemberId": 2786,
"createdAt": "2017-01-18 01:10",
"type": "ORGANIZATION",
"role": "BACKER",
"isActive": true,
"totalAmountDonated": 8000,
"currency": "USD",
"lastTransactionAt": "2019-08-18 05:00",
"lastTransactionAmount": 250,
"profile": "https://opencollective.com/eggheadio",
"name": "egghead.io",
"company": null,
"description": null,
"image": "https://logo.clearbit.com/egghead.io",
"email": null,
"twitter": "https://twitter.com/eggheadio",
"github": null,
"website": "https://egghead.io"
},
{
"MemberId": 3613,
"createdAt": "2017-03-17 14:01",
"type": "ORGANIZATION",
"role": "BACKER",
"isActive": true,
"totalAmountDonated": 60000,
"currency": "USD",
"lastTransactionAt": "2019-08-01 05:37",
"lastTransactionAmount": 2500,
"profile": "https://opencollective.com/ag-grid",
"name": "ag-Grid",
"company": "Limited registered in the United Kingdom. Company No. 07318192.",
"description": "Our mission is simple: Build the best Javascript datagrid in the world. Designed for Enterprise applications delivering features and performance for your chosen framework.",
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/89305d30-0ccc-11e8-8c0a-8594e8ca6b48.png",
"email": null,
"twitter": "https://twitter.com/ag_grid",
"github": null,
"website": "https://www.ag-grid.com/"
},
{
"MemberId": 45211,
"createdAt": "2019-07-05 12:02",
"type": "ORGANIZATION",
"role": "BACKER",
"isActive": true,
"totalAmountDonated": 3737,
"lastTransactionAt": "2019-08-26 19:21",
"lastTransactionAmount": 0,
"profile": "https://opencollective.com/triplebyte",
"name": "Triplebyte",
"company": null,
"description": "Triplebyte is the first software engineering job platform that is on the developer's side. Take our coding quiz!",
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/02f87560-b2f1-11e8-85a0-75f200a0e2db.png",
"email": null,
"twitter": "https://twitter.com/triple_byte",
"github": null,
"website": "https://triplebyte.com/os/opencollective"
},
{
"MemberId": 50274,
"createdAt": "2019-08-25 17:00",
"type": "ORGANIZATION",
"role": "BACKER",
"tier": "Backer",
"isActive": false,
"totalAmountDonated": 3737,
"lastTransactionAt": "2019-08-26 19:21",
"lastTransactionAmount": 0,
"profile": "https://opencollective.com/triplebyte",
"name": "Triplebyte",
"company": null,
"description": "Triplebyte is the first software engineering job platform that is on the developer's side. Take our coding quiz!",
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/02f87560-b2f1-11e8-85a0-75f200a0e2db.png",
"email": null,
"twitter": "https://twitter.com/triple_byte",
"github": null,
"website": "https://triplebyte.com/os/opencollective"
},
{
"MemberId": 43659,
"createdAt": "2019-06-21 08:34",
"type": "ORGANIZATION",
"role": "BACKER",
"tier": "Backer",
"isActive": true,
"totalAmountDonated": 6,
"currency": "USD",
"lastTransactionAt": "2019-08-01 05:24",
"lastTransactionAmount": 2,
"profile": "https://opencollective.com/traders-insurance-com",
"name": "Traders-Insurance.com",
"company": null,
"description": "Compare UK Motor Trade Insurance Providers",
"image": "https://opencollective-production.s3.us-west-1.amazonaws.com/d2678f20-935b-11e9-acfe-430642a0fdd0.png",
"email": null,
"twitter": "https://twitter.com/trademotor",
"github": null,
"website": "https://www.Traders-Insurance.com"
},
{
"MemberId": 49249,
"createdAt": "2019-08-14 16:00",
"type": "ORGANIZATION",
"role": "BACKER",
"isActive": true,
"totalAmountDonated": 3737,
"lastTransactionAt": "2019-08-26 19:21",
"lastTransactionAmount": 0,
"profile": "https://opencollective.com/triplebyte",
"name": "Triplebyte",
"company": null,
"description": "Triplebyte is the first software engineering job platform that is on the developer's side. Take our coding quiz!",
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/02f87560-b2f1-11e8-85a0-75f200a0e2db.png",
"email": null,
"twitter": "https://twitter.com/triple_byte",
"github": null,
"website": "https://triplebyte.com/os/opencollective"
},
{
"MemberId": 49251,
"createdAt": "2019-08-14 16:01",
"type": "ORGANIZATION",
"role": "BACKER",
"isActive": true,
"totalAmountDonated": 3737,
"lastTransactionAt": "2019-08-26 19:21",
"lastTransactionAmount": 0,
"profile": "https://opencollective.com/triplebyte",
"name": "Triplebyte",
"company": null,
"description": "Triplebyte is the first software engineering job platform that is on the developer's side. Take our coding quiz!",
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/02f87560-b2f1-11e8-85a0-75f200a0e2db.png",
"email": null,
"twitter": "https://twitter.com/triple_byte",
"github": null,
"website": "https://triplebyte.com/os/opencollective"
},
{
"MemberId": 43529,
"createdAt": "2019-06-19 19:49",
"type": "ORGANIZATION",
"role": "BACKER",
"isActive": true,
"totalAmountDonated": 5,
"currency": "USD",
"lastTransactionAt": "2019-06-19 19:49",
"lastTransactionAmount": 5,
"profile": "https://opencollective.com/casino-rabatter1",
"name": "Casino rabatter",
"company": null,
"description": null,
"image": "https://opencollective-production.s3.us-west-1.amazonaws.com/8214b690-92cc-11e9-a99c-49812773900b.png",
"email": null,
"twitter": null,
"github": null,
"website": "http://www.casinorabatter.se/"
},
{
"MemberId": 46693,
"createdAt": "2019-07-20 14:04",
"type": "ORGANIZATION",
"role": "BACKER",
"tier": "Backer",
"isActive": true,
"totalAmountDonated": 4,
"currency": "USD",
"lastTransactionAt": "2019-08-01 05:25",
"lastTransactionAmount": 2,
"profile": "https://opencollective.com/casinomucho",
"name": "Casinomucho",
"company": null,
"description": "Quality online casino comparison platform built for community of UK players",
"image": "https://logo.clearbit.com/casinomucho.com",
"email": null,
"twitter": null,
"github": null,
"website": "https://casinomucho.com/"
},
{
"MemberId": 13446,
"createdAt": "2018-03-02 22:48",
"type": "ORGANIZATION",
"role": "BACKER",
"tier": "Sponsor",
"isActive": true,
"totalAmountDonated": 10000,
"currency": "USD",
"lastTransactionAt": "2019-08-02 05:01",
"lastTransactionAmount": 500,
"profile": "https://opencollective.com/amp",
"name": "AMP Project",
"company": "",
"description": null,
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/68ed8b70-ebf2-11e6-9958-cb7e79408c56.png",
"email": null,
"twitter": "https://twitter.com/amphtml",
"github": null,
"website": "https://www.ampproject.org/"
},
{
"MemberId": 3821,
"createdAt": "2017-03-30 03:20",
"type": "ORGANIZATION",
"role": "BACKER",
"tier": "Sponsor",
"isActive": true,
"totalAmountDonated": 3398,
"currency": "USD",
"lastTransactionAt": "2019-08-01 05:36",
"lastTransactionAmount": 200,
"profile": "https://opencollective.com/icons8",
"name": "Free Icons by Icons8",
"company": null,
"description": "Making the icons for front-end developers",
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/5c6ca1a0-5abe-11e9-adb1-e17fccd4c65e.png",
"email": null,
"twitter": "https://twitter.com/visualpharm",
"github": null,
"website": "https://icons8.com"
},
{
"MemberId": 8248,
"createdAt": "2017-10-26 16:48",
"type": "ORGANIZATION",
"role": "BACKER",
"tier": "Sponsor",
"isActive": true,
"totalAmountDonated": 23000,
"currency": "USD",
"lastTransactionAt": "2019-08-02 05:04",
"lastTransactionAmount": 1000,
"profile": "https://opencollective.com/fbopensource",
"name": "Facebook Open Source",
"company": null,
"description": "Facebook Open Source Team",
"image": "https://res.cloudinary.com/opencollective/image/upload/v1508519428/S9gk78AS_400x400_fulq2l.jpg",
"email": null,
"twitter": "https://twitter.com/fbOpenSource",
"github": null,
"website": "https://code.facebook.com/projects/"
},
{
"MemberId": 7691,
"createdAt": "2017-10-12 00:00",
"type": "ORGANIZATION",
"role": "BACKER",
"isActive": true,
"totalAmountDonated": 26034,
"currency": "USD",
"lastTransactionAt": "2019-08-01 05:20",
"lastTransactionAmount": 1094,
"profile": "https://opencollective.com/airbnb",
"name": "Airbnb",
"company": null,
"description": "Book unique homes and experience a city like a local.",
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/098e3bd0-4d57-11e8-9324-0f6cc1f92bf1.png",
"email": null,
"twitter": "https://twitter.com/airbnbeng",
"github": null,
"website": "https://www.airbnb.com/"
},
{
"MemberId": 8063,
"createdAt": "2017-10-21 20:43",
"type": "ORGANIZATION",
"role": "BACKER",
"tier": "Backer",
"isActive": true,
"totalAmountDonated": 46,
"currency": "USD",
"lastTransactionAt": "2019-08-02 05:01",
"lastTransactionAmount": 2,
"profile": "https://opencollective.com/artivilla",
"name": "Arti Villa",
"company": null,
"description": null,
"image": null,
"email": null,
"twitter": "https://twitter.com/artivilla",
"github": null,
"website": "https://writing.artivilla.com"
},
{
"MemberId": 8158,
"createdAt": "2017-10-24 12:28",
"type": "ORGANIZATION",
"role": "BACKER",
"tier": "Backer",
"isActive": false,
"totalAmountDonated": 20,
"currency": "USD",
"lastTransactionAt": "2017-10-24 12:28",
"lastTransactionAmount": 20,
"profile": "https://opencollective.com/crazygamescom1",
"name": "Maxflow BVBA (BE 0550.758.377)",
"company": null,
"description": null,
"image": "https://logo.clearbit.com/crazygames.com",
"email": null,
"twitter": "https://twitter.com/crazyGamesCom",
"github": null,
"website": "https://www.crazygames.com"
},
{
"MemberId": 8239,
"createdAt": "2017-10-26 13:28",
"type": "ORGANIZATION",
"role": "BACKER",
"tier": "Backer",
"isActive": false,
"totalAmountDonated": 2,
"currency": "USD",
"lastTransactionAt": "2017-10-26 13:28",
"lastTransactionAmount": 2,
"profile": "https://opencollective.com/_brainly_",
"name": "Brainly",
"company": null,
"description": " Brainly brings the world's students into a community of learners. At Brainly, millions of students team up to share ideas, explore knowledge, and solve problems.",
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/63435090-ba52-11e7-a545-6dcd8fd564a8.png",
"email": null,
"twitter": null,
"github": null,
"website": "http://brainly.com"
},
{
"MemberId": 10384,
"createdAt": "2017-12-06 02:01",
"type": "ORGANIZATION",
"role": "BACKER",
"isActive": true,
"totalAmountDonated": 10,
"currency": "USD",
"lastTransactionAt": "2017-12-06 02:01",
"lastTransactionAmount": 10,
"profile": "https://opencollective.com/elegant-media",
"name": "Elegant Media",
"company": null,
"description": "Melbourne Based iPhone, Android App and Web Development Agency",
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/34d2a0b0-da2a-11e7-867c-87d1567b2ae3.jpg",
"email": null,
"twitter": null,
"github": null,
"website": "http://www.elegantmedia.com.au/"
},
{
"MemberId": 11176,
"createdAt": "2018-01-05 01:25",
"type": "ORGANIZATION",
"role": "BACKER",
"tier": "Sponsor",
"isActive": false,
"totalAmountDonated": 200,
"currency": "USD",
"lastTransactionAt": "2018-01-05 01:25",
"lastTransactionAmount": 200,
"profile": "https://opencollective.com/mixmax",
"name": "Mixmax",
"company": null,
"description": "The future of professional communication",
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/fcf6c0d0-f730-11e7-af8c-05ca2e1ddbda.png",
"email": null,
"twitter": "https://twitter.com/Mixmax",
"github": "https://github.com/mixmaxhq",
"website": "https://mixmax.com"
},
{
"MemberId": 11044,
"createdAt": "2017-12-31 00:08",
"type": "ORGANIZATION",
"role": "BACKER",
"tier": "Backer",
"isActive": false,
"totalAmountDonated": 12,
"currency": "USD",
"lastTransactionAt": "2018-05-01 05:10",
"lastTransactionAmount": 2,
"profile": "https://opencollective.com/pcwarecomco1",
"name": "Elberth Jaimes",
"company": null,
"description": null,
"image": "https://logo.clearbit.com/pcware.com.co",
"email": null,
"twitter": "https://twitter.com/pcwarecomco",
"github": null,
"website": "https://pcware.com.co/categoria-producto/computadores-portatiles/"
},
{
"MemberId": 11476,
"createdAt": "2018-01-15 09:23",
"type": "ORGANIZATION",
"role": "BACKER",
"tier": "Backer",
"isActive": true,
"totalAmountDonated": 40,
"currency": "USD",
"lastTransactionAt": "2019-08-02 05:02",
"lastTransactionAmount": 2,
"profile": "https://opencollective.com/biohackers-lab",
"name": "Biohackers Lab",
"company": null,
"description": "❤️ Biohacking - Listen 🎧 To Our #Health Podcast + Follow Us",
"image": "https://pbs.twimg.com/profile_images/902788674831740928/ug0tyll1.jpg",
"email": null,
"twitter": "https://twitter.com/biohackerslab",
"github": null,
"website": "http://www.biohackerslab.com"
},
{
"MemberId": 12510,
"createdAt": "2018-02-10 02:52",
"type": "ORGANIZATION",
"role": "BACKER",
"isActive": true,
"totalAmountDonated": 250,
"currency": "USD",
"lastTransactionAt": "2018-11-01 05:15",
"lastTransactionAmount": 25,
"profile": "https://opencollective.com/codepilotai",
"name": "CodePilot.ai",
"company": null,
"description": "Dev team building \"Google for Developers\" an awesome search tool to find faster answers to your code problems.",
"image": "https://logo.clearbit.com/codepilot.ai",
"email": null,
"twitter": "https://twitter.com/codepilotai",
"github": "https://github.com/CodePilotai/codepilot",
"website": "http://codepilot.ai"
},
{
"MemberId": 12756,
"createdAt": "2018-02-15 16:39",
"type": "ORGANIZATION",
"role": "BACKER",
"tier": "Backer",
"isActive": true,
"totalAmountDonated": 190,
"currency": "USD",
"lastTransactionAt": "2019-08-01 05:01",
"lastTransactionAmount": 10,
"profile": "https://opencollective.com/matterstech",
"name": "Matters",
"company": null,
"description": "Startup Studio",
"image": "https://opencollective-production.s3-us-west-1.amazonaws.com/2d0ca280-1270-11e8-baae-774588f2a4fb.png",
"email": null,
"twitter": "https://twitter.com/matterstech",
"github": null,
"website": "http://matters.tech"
},
{
"MemberId": 40688,
"createdAt": "2019-05-21 05:59",
"type": "ORGANIZATION",
"role": "BACKER",
"isActive": true,
"totalAmountDonated": 20,
"currency": "USD",
```

```swift
1. The current stock price of Microsoft. (IEX API)

https://api.worldtradingdata.com/api/v1/stock?symbol=AAPL,MSFT,HSBA.L&api_token=demo

"message": "This request is for demonstration purposes only. If you wish to use our API, please sign up and get your personal API token for free.",
"symbols_requested": 3,
"symbols_returned": 3,
"data": [
{
"symbol": "AAPL",
"name": "Apple Inc.",
"currency": "USD",
"price": "206.05",
"price_open": "205.86",
"day_high": "207.19",
"day_low": "205.06",
"52_week_high": "233.47",
"52_week_low": "142.00",
"day_change": "3.41",
"change_pct": "1.68",
"close_yesterday": "202.64",
"market_cap": "931177037824",
"volume": "20682063",
"volume_avg": "28254233",
"shares": "4601079808",
"stock_exchange_long": "NASDAQ Stock Exchange",
"stock_exchange_short": "NASDAQ",
"timezone": "EDT",
"timezone_name": "America/New_York",
"gmt_offset": "-14400",
"last_trade_time": "2019-08-26 15:19:01"
},
{
"symbol": "HSBA.L",
"name": "HSBC Holdings plc",
"currency": "GBX",
"price": "586.40",
"price_open": "596.00",
"day_high": "596.90",
"day_low": "586.40",
"52_week_high": "695.90",
"52_week_low": "586.40",
"day_change": "-7.30",
"change_pct": "-1.23",
"close_yesterday": "593.70",
"market_cap": "720242535093",
"volume": "30001796",
"volume_avg": "34950977",
"shares": "20216616020",
"stock_exchange_long": "London Stock Exchange",
"stock_exchange_short": "LSE",
"timezone": "BST",
"timezone_name": "Europe/London",
"gmt_offset": "3600",
"last_trade_time": "2019-08-23 16:38:43"
},
{
"symbol": "MSFT",
"name": "Microsoft Corporation",
"currency": "USD",
"price": "135.17",
"price_open": "134.99",
"day_high": "135.45",
"day_low": "133.91",
"52_week_high": "141.68",
"52_week_low": "93.96",
"day_change": "1.78",
"change_pct": "1.33",
"close_yesterday": "133.39",
"market_cap": "1032078360576",
"volume": "13593751",
"volume_avg": "23691916",
"shares": "7662819840",
"stock_exchange_long": "NASDAQ Stock Exchange",
"stock_exchange_short": "NASDAQ",
"timezone": "EDT",
"timezone_name": "America/New_York",
"gmt_offset": "-14400",
"last_trade_time": "2019-08-26 15:18:58"
}
]
}
```
```swift

1. The 5 year history of Apple stock prices (IEX API)

https://api.worldtradingdata.com/api/v1/history?symbol=AAPL&sort=newest&api_token=demo

"name": "AAPL",
"history": {
"2019-08-23": {
"open": "209.43",
"close": "202.64",
"high": "212.05",
"low": "201.00",
"volume": "46882843"
},
"2019-08-22": {
"open": "213.19",
"close": "212.46",
"high": "214.44",
"low": "210.75",
"volume": "22267819"
},
"2019-08-21": {
"open": "212.99",
"close": "212.64",
"high": "213.65",
"low": "211.60",
"volume": "21564747"
},
"2019-08-20": {
"open": "210.88",
"close": "210.36",
"high": "213.35",
"low": "210.32",
"volume": "26919529"
},
"2019-08-19": {
"open": "210.62",
"close": "210.35",
"high": "212.73",
"low": "210.03",
"volume": "24431915"
},
"2019-08-16": {
"open": "204.28",
"close": "206.50",
"high": "207.16",
"low": "203.84",
"volume": "28813624"
},
"2019-08-15": {
"open": "203.46",
"close": "201.74",
"high": "205.14",
"low": "199.67",
"volume": "27883363"
},
"2019-08-14": {
"open": "203.16",
"close": "202.75",
"high": "206.44",
"low": "202.59",
"volume": "36547443"
},
"2019-08-13": {
"open": "201.02",
"close": "208.97",
"high": "212.14",
"low": "200.83",
"volume": "47539786"
},
"2019-08-12": {
"open": "199.62",
"close": "200.48",
"high": "202.05",
"low": "199.15",
"volume": "22481889"
},
"2019-08-09": {
"open": "201.30",
"close": "200.99",
"high": "202.76",
"low": "199.29",
"volume": "24619746"
},
"2019-08-08": {
"open": "200.20",
"close": "203.43",
"high": "203.53",
"low": "199.39",
"volume": "27009523"
},
"2019-08-07": {
"open": "195.41",
"close": "199.04",
"high": "199.56",
"low": "193.82",
"volume": "33364400"
},
"2019-08-06": {
"open": "196.31",
"close": "197.00",
"high": "198.07",
"low": "194.04",
"volume": "35824787"
},
"2019-08-05": {
"open": "197.99",
"close": "193.34",
"high": "198.65",
"low": "192.58",
"volume": "52392969"
},
"2019-08-02": {
"open": "205.53",
"close": "204.02",
"high": "206.43",
"low": "201.63",
"volume": "40862122"
},
"2019-08-01": {
"open": "213.90",
"close": "208.43",
"high": "218.03",
"low": "206.74",
"volume": "54017922"
},
"2019-07-31": {
"open": "216.42",
"close": "213.04",
"high": "221.37",
"low": "211.30",
"volume": "69281361"
},
"2019-07-30": {
"open": "208.76",
"close": "208.78",
"high": "210.16",
"low": "207.31",
"volume": "33935718"
},
"2019-07-29": {
"open": "208.46",
"close": "209.68",
"high": "210.64",
"low": "208.44",
"volume": "21673389"
},
"2019-07-26": {
"open": "207.48",
"close": "207.74",
"high": "209.73",
"low": "207.14",
"volume": "17618874"
},
"2019-07-25": {
"open": "208.89",
"close": "207.02",
"high": "209.24",
"low": "206.73",
"volume": "13909562"
}
```
```swift

1. All the Swift language repos on Github with Pursuit in their name

https://api.github.com/search/users?q=pursuit+language:swift

"total_count": 12,
"incomplete_results": false,
"items": [
{
"login": "joinpursuit",
"id": 5825944,
"node_id": "MDEyOk9yZ2FuaXphdGlvbjU4MjU5NDQ=",
"avatar_url": "https://avatars2.githubusercontent.com/u/5825944?v=4",
"gravatar_id": "",
"url": "https://api.github.com/users/joinpursuit",
"html_url": "https://github.com/joinpursuit",
"followers_url": "https://api.github.com/users/joinpursuit/followers",
"following_url": "https://api.github.com/users/joinpursuit/following{/other_user}",
"gists_url": "https://api.github.com/users/joinpursuit/gists{/gist_id}",
"starred_url": "https://api.github.com/users/joinpursuit/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/joinpursuit/subscriptions",
"organizations_url": "https://api.github.com/users/joinpursuit/orgs",
"repos_url": "https://api.github.com/users/joinpursuit/repos",
"events_url": "https://api.github.com/users/joinpursuit/events{/privacy}",
"received_events_url": "https://api.github.com/users/joinpursuit/received_events",
"type": "Organization",
"site_admin": false,
"score": 69.310875
},
{
"login": "EliPeraza",
"id": 36087532,
"node_id": "MDQ6VXNlcjM2MDg3NTMy",
"avatar_url": "https://avatars3.githubusercontent.com/u/36087532?v=4",
"gravatar_id": "",
"url": "https://api.github.com/users/EliPeraza",
"html_url": "https://github.com/EliPeraza",
"followers_url": "https://api.github.com/users/EliPeraza/followers",
"following_url": "https://api.github.com/users/EliPeraza/following{/other_user}",
"gists_url": "https://api.github.com/users/EliPeraza/gists{/gist_id}",
"starred_url": "https://api.github.com/users/EliPeraza/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/EliPeraza/subscriptions",
"organizations_url": "https://api.github.com/users/EliPeraza/orgs",
"repos_url": "https://api.github.com/users/EliPeraza/repos",
"events_url": "https://api.github.com/users/EliPeraza/events{/privacy}",
"received_events_url": "https://api.github.com/users/EliPeraza/received_events",
"type": "User",
"site_admin": false,
"score": 38.51791
},
{
"login": "jalmonte83",
"id": 43770785,
"node_id": "MDQ6VXNlcjQzNzcwNzg1",
"avatar_url": "https://avatars1.githubusercontent.com/u/43770785?v=4",
"gravatar_id": "",
"url": "https://api.github.com/users/jalmonte83",
"html_url": "https://github.com/jalmonte83",
"followers_url": "https://api.github.com/users/jalmonte83/followers",
"following_url": "https://api.github.com/users/jalmonte83/following{/other_user}",
"gists_url": "https://api.github.com/users/jalmonte83/gists{/gist_id}",
"starred_url": "https://api.github.com/users/jalmonte83/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/jalmonte83/subscriptions",
"organizations_url": "https://api.github.com/users/jalmonte83/orgs",
"repos_url": "https://api.github.com/users/jalmonte83/repos",
"events_url": "https://api.github.com/users/jalmonte83/events{/privacy}",
"received_events_url": "https://api.github.com/users/jalmonte83/received_events",
"type": "User",
"site_admin": false,
"score": 36.09697
},
{
"login": "pursuitstudent777",
"id": 52424231,
"node_id": "MDQ6VXNlcjUyNDI0MjMx",
"avatar_url": "https://avatars0.githubusercontent.com/u/52424231?v=4",
"gravatar_id": "",
"url": "https://api.github.com/users/pursuitstudent777",
"html_url": "https://github.com/pursuitstudent777",
"followers_url": "https://api.github.com/users/pursuitstudent777/followers",
```
```swift

1. A list of all Pokemon

https://pokeapi.co/api/v2/pokemon/

"count": 964,
"next": "https://pokeapi.co/api/v2/pokemon/?offset=20&limit=20",
"previous": null,
"results": [
{
"name": "bulbasaur",
"url": "https://pokeapi.co/api/v2/pokemon/1/"
},
{
"name": "ivysaur",
"url": "https://pokeapi.co/api/v2/pokemon/2/"
},
{
"name": "venusaur",
"url": "https://pokeapi.co/api/v2/pokemon/3/"
}
```
```swift

1. A list of all items in Fortnite

api.fortnitetracker.com/v1/store/
```
```swift

1. A list of all Game of Thrones Episodes.

https://api.got.show/api/show/episodes

"_id": "5cc074bf04e71a0010b85a1a",
"title": "Winter Is Coming",
"season": 1,
"episode": 1,
"runtime": 62,
"directed_by": "Tim Van Patten",
"createdAt": "2019-04-24T14:37:51.759Z",
"updatedAt": "2019-04-24T14:37:51.759Z",
"__v": 0
```

1. A list of all songs with "Love" in the title.



```swift
1. All information about Petyr Baelish from the Game of Thrones books

https://www.anapioficeandfire.com/api/characters/823

"url": "https://anapioficeandfire.com/api/characters/823",
"name": "Petyr Baelish",
"gender": "Male",
"culture": "Valemen",
"born": "In 268 AC, at the Fingers",
"died": "",
"titles": [
"Master of coin (formerly)",
"Lord Paramount of the Trident",
"Lord of Harrenhal",
"Lord Protector of the Vale"
],
"aliases": [
"Littlefinger"
```

1. All the movies Leonardo Dicaprio has acted in
```swift
freemusicarchive.org/api/track_title?q=love&limit=100
```
A
