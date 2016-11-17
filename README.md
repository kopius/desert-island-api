# Desert Island

## The Story of Desert Island

In today's world of unlimited data plans, gigs upon gigs of storage space, and
social media feeds that push new photos off the page faster than you can upload
them, we wondered...

**...what if an online photo album only let you upload five images?**

Not because of storage limits, or arbitrary usage fees, but simply as an
exercise in self-definition and discipline. How would you sum yourself up in
five pictures?

The idea for our app rose up out of this question. If you were stranded on a
desert island with nothing but your wits and a 4G smartphone, what five image
files would you want to have stored in the cloud? If these photos were the only
way you could communicate with your fellow castaways on distant shores, what
would you want them to see?

Introducing...**Desert Island.**

[Link to Client Repo](https://github.com/kopius/desert-island)
||
[Link to Deployed Client](https://kopius.github.io/desert-island)

## API endpoints

| Verb   | URI Pattern            | Controller#Action |
| ----   | -----------            | ----------------- |
| POST   | `/sign-up`             | `users#signup`    |
| POST   | `/sign-in`             | `users#signin`    |
| DELETE | `/sign-out/:id`        | `users#signout`   |
| PATCH  | `/change-password/:id` | `users#changepw`  |
| GET    | `/users`               | `users#index`     |
| GET    | `/users/:id`           | `users#show`      |
| POST   | `/uploads`             | `uploads#create`  |
| GET    | `/uploads`             | `uploads#index`   |
| GET    | `/uploads/:id`         | `uploads#show`    |
| PATCH  | `/uploads/:id`         | `uploads#update`  |
| DELETE | `/uploads/:id`         | `uploads#destroy` |
