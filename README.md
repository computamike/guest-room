# guest-room
I had an idea - What if the Google Chromecast on the spare room TV could provide useful information to visitors to our house? Like how to get on the guest Wifi - how to access the media server etc.

So the idea is that the chromecast becomes available on the network.  A server will look for the presence of a chromecast, and then push the reciever to the cast device.

So - What are we we writing this in?
Well as I'm now a javascript developer I'll be looking at doing this in javascript.

Challenge 0: How to run a node app as a service

Challenge 1 : How do I know if an IP Address is on the network?

Challenge 2 : How do I push a reciever to the ChromeCast

Challenge 3 : How do I only push to new guests?

Challenge 4 : What should I push

# Adonis fullstack application

This is the fullstack boilerplate for AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Session
3. Authentication
4. Web security middleware
5. CORS
6. Edge template engine
7. Lucid ORM
8. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick
```

or manually clone the repo and then run `npm install`.


### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```
