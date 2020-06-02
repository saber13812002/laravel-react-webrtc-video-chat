## Video Chat Application Example

[Youtube Tutorial link](https://www.youtube.com/watch?v=5pnsloZzYQM)

#### [@WeCodeTutorials](https://twitter.com/WeCodeTutorials)
[![Logo](https://cdn.pbrd.co/images/HdwCut8.png)](https://www.youtube.com/channel/UCj9VatwdukZjNOnIKcpWcsA)

#### WebRTC Project
[![Logo](https://webrtc.org/assets/images/webrtc-logo-horiz-retro-243x40.png)](https://webrtc.org/)

This project is made for my youtube tutorial on "Create a video Chat Application with Laravel & ReactJS (based on WebRTC)".

## get it up and running.

After you clone this project, do the following:

```
bash

```
# go into the project

```
cd video-chat-example
```

# create a .env file

```
cp .env.example .env
```

# install composer dependencies

```
composer update
```

# install npm dependencies

```
npm install
```

# generate a key for your application

```
php artisan key:generate
```

# create a file for your SQLite database

```
touch database/database.sqlite
```

if you want to use sqllite

# mrun the migration files to generate the schema

```
php artisan migrate
```

if use sql lite your env file DB block should look like this:

```
DB_CONNECTION=sqlite

#DB_HOST=127.0.0.1

#DB_PORT=3306

#DB_DATABASE=database

#DB_USERNAME=homestead

#DB_PASSWORD=secret

```

# run webpack and watch for changes
```
npm run watch
```

enjoy & Good Luck :)
