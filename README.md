# Laugh Generator

The Laugh Generator was created during the current pandemic because there was not much to laugh about in life. We decided to make a random joke generator that spits out a random joke taken from an open source joke API at the touch of a button. Afterwards, you can share that joke with your friends on Twitter, Reddit and Facebook with the simple touch of another button. Later, we added the ability for our generator to pull memes off of reddit, and also filter out potentially nsfw memes.

Your most recent joke/meme generated for you is saved to Local Storage, so it will still be there in case you accidentally refresh the page.

The Laugh Generator also includes a list of filters and categories that allow you to customize your user experience with only the jokes you want to see.


[The standard Laugh Generator desktop page with a joke](./assets/Laugh.png)
[The standard Laugh Generator desktop page with a meme](./assets/Meme.png)
[The Mobile Version of Laugh Generator with a joke](./assets/Mobile.png)
[The Mobile Version of Laugh Generator with a meme](./assets/Mememobile.png)


# How to use the Customization Feature:

[The Desktop Page with the Filters and Categories menu open](./assets/Filters.png)
[The Mobile Page with the Filters and Categories menu open](./assets/Filtersmobile.png)

## FILTERS:


This list of options is where you can choose to ![NOT] view jokes that may offend you.
This is a blacklist, so checking the boxes will ![PREVENT] you from seeing jokes in the following categories:
NSFW: Jokes that are not safe for work. Check this box if you are in a family-safe environment and do ![NOT] want to see this content.
Religious: Jokes that contain potentially offensive religious content. Check this box if you do ![NOT] want to see religious jokes.
Political: Jokes about recent political topics and figures. Check this box if you do ![NOT] want to see any jokes about poltics.
Racist: Offensive jokes about race. Check this box if you do ![NOT] want to see racist jokes.
Sexist: Offensive jokes about gender differences. Check this box if you do ![NOT] want to see jokes involving sexism
Explicit: Jokes with explicit content, including but not limited to sexual humor. Check this box if you do ![NOT] want to see these kinds of jokes.


## CATEGORIES:

This list of options includes specific themes of jokes. Unlike the Filters list, check these boxes if you want to ![INCLUDE] these themes. If none of the boxes in categories are checked, it will display a joke from any of the categories listed. If only one box is selected, for instance, "Christmas", it will only display Christmas themed jokes. If two or more boxes are selected, it will display jokes taken from one of the categories selected.

Programming: Jokes about programming. Check this box if you ![WANT] to see these kinds of jokes.
Misc: Jokes that don't fall in any category. (For the API to work, this must be choice number 2.) Check this box if you ![WANT] to see jokes that do not fall in the other categories.
Dark: Morbid jokes usually about death and other dark topics. Check this box if you ![WANT] to see these kinds of jokes.
Pun: Wordplay. Check this box if you ![WANT] to see puns.
Spooky: Jokes good for Halloween and other spooky events. Check this box if you ![WANT] to see fun jokes about ghosts, skeletons, and the like.
Christmas: Jokes good for Christmas. Self-explanatory. Check this box if you ![WANT] to see Christmas themed jokes.

# Memes:

Memes work differently from Jokes as they are pulled from another API. NSFW content is automatically filtered out from memes because they are pulled directly from Reddit. The plus side of this is that the memes should be current.


# Sharing:

Pressing the Twitter, Reddit, and Facebook buttons shares the jokes and memes to Twitter and Reddit. Unfortunately, due to how facebook works, it only shares a link to the Laugh Generator at the moment.

# APIs used:

* [JokeAPI](https://sv443.net/jokeapi/v2/)
* [MemeAPI](https://github.com/D3vd/Meme_Api)

## APIs we WANTED to use, but they never got back to us:
* [Twitter](https://developer.twitter.com/en/docs/twitter-api)
* [Reddit](https://www.reddit.com/dev/api)
* [Facebook](https://developers.facebook.com/docs/apis-and-sdks)


## Credits:

Made by Team Funny-Jokes

Nelson Rosado
Joseph Valancy
Emily Fernandez
Fernando Zaldivar