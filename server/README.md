# Civitas

### APIs

#### signup.router.js

POST `/api/signup/regular`

POST `/api/signup/admin`

#### auth.router.js

POST `/api/authorize` 

POST `/api/authorize/login`

POST `/api/authorize/getid`

#### group.router.js

POST `/api/group/create`

POST `/api/group/:group_id`

PATCH `/api/group/invite/:group_id`

PATCH `/api/group/join/:group_id`

#### posts.router.js

GET `/api/posts`

POST `/api/posts`

GET `/api/posts/:post_id`

PATCH `/api/posts/:post_id`

DELETE `/api/posts/:post_id`

#### comment.router.js

POST `/api/comments/create-comment`

DELETE `/api/comments/:comment_id`

#### announcement.router.js
POST `/api/announcements/`

DELETE `/api/announcements/`
