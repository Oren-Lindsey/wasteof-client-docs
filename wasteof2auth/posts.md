# wasteof2auth posts

- post `wasteof2.post(content, repost)`: makes a new post. can have html or plain text content

    options: content (content you want to post), repost (id of post you want to repost, set to `null` for no repost)
- comment on a post `wasteof2.postComment(id, content, parent)`: posts a comment on a post

    options: id (id of post to comment on), content (what to post), parent (id of comment you want to reply to)
- edit post `wasteof2.editPost(id, content)`: edits a post

    options: id (id of post to edit), content (content to change the post to)
- delete post `wasteof2.deletePost(id)`: deletes a post

    options: id (id of post to delete)
- delete comment `wasteof2.deleteComment(id)`: deletes a post comment (not a wall comment)

    options: id (id of comment to delete)
- pin post `wasteof2.pinPost(id)`: pins a post on your profile

    options: id (id of post to pin)
- unpin post `wasteof2.unpinPost(id)`: unpins a post from your profile

    options: id (id of post to unpin)
- report post `wasteof2.reportPost(id, reason)`: reports a post

    options: id (id of post to report), reason (reason why you want to report this post)
- toggle loving a post `wasteof2.toggleLove(id)`: toggles whether you are loving a certain post

    options: id (id of post to toggle)