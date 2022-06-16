# wasteof2 users

- get user data `wasteof2.getUser(name)`: gets a user's data. I would use the wasteof3 version as it provides richer data.

    options: name (username)
- get users posts `wasteof2.getPostsOfUser(name, page)`: get a user's posts, paged

    options: name (username), page (page of posts)
- get followers of a user `wasteof2.getFollowersOfUser(name)`: get a user's followers. again, i would use the wasteof3 version

    options: name (username)
- get if one user is following another `wasteof2.getIfUserIsFollowingUser(user1, user2)`: probably the most complicated method, checks if user1 is following user2

    options: user1 (username of user who might be following user2), user2 (username of user who might be followed by user1)
- get following `wasteof2.getFollowingOfUser(name)`: find who a user is following

    options: name (username to get)
- get profile picture `wasteof2.getPicture(name)`: gets a user's profile picture. I haven't tested this out but i think it works. Let's just say its in beta...

    options: name (username to get)
- get banner `wasteof2.getBanner(name)`: gets a user's banner. I also haven't tested this one. Also in beta

    options: name (username to get)
- get feed of user `wasteof2.getFeedOfUser(name, page)`: gets a user's feed, paged

    options: name (username), page (page of feed)
- join `wasteof2.join(name, password, captcha)`: joins wasteof.money, requires a captcha code. I'm not even remotely sure how you'd obtain a captcha but whatever...

    options: name (name to join with), password, captcha (captcha code)

    I've actually tried to do this before and it seems that the same captcha code can be used multiple times, so maybe you'd do the captcha online, get the code from the request, and put it in here??
