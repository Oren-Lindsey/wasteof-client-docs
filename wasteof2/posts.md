# wasteof2 posts

- get post data `wasteof2.getPost(id)`: gets data about a post. Again, i would use the wasteof3 version

options: id (post id)
- get comments on post `wasteof2.getCommentsOnPost(id, page)`: get comments on a post, paged

options: id (post id), page (page of comments)
- get replies to comment `wasteof2.getRepliesToComment(id, page)`: self explanatory

options: id (comment id), page (page of results)
- get if user loved post `wasteof2.getIfUserLovedPost(id, name)`: check if a certain user loved a certain post

options: id (post id), name (name of user)