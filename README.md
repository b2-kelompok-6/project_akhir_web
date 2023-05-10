# BIGETRON SHOP

![Bigetron Esports Logo](https://github.com/neladwi/2109116078_Nela-Dwi-Anggraini_Toko-Ice-Cream/assets/120194377/7fb176ee-9137-44d3-9066-0be5d1856d98)


# BIGETRON SHOP

Bigetron Shop merupakan sebuah aplikasi yang dirancang untuk membeli produk Merchandise Esports Bigetron dengan kualitas terbaik. Pelanggan dapat membeli aneka produk di Toko Bigetron Shop secara online dengan aman dan mudah. 

## Fitur Aplikasi
Beberapa fitur yang terdaapt di dalam aplikasi yaitu, sebagai berikut:
1. 🏠Home - Keep a track of your personal goals. You can use todolist to keep track of your goals progress or use payments submodule to keep an eye of the money amount that you want to collect for something.
Fitur:
Tampilan Awal:
-Home
-About
-Profile
-Sign In
-Shop
Halaman Admin
-Tambah Barang
-Edit Barang
Halaman Staff
-
-
Halaman User
-
-

Features:

User Login: This contains all the tools and options required by any user who's willing to book a hotel room.
Admin Login: This contains all the controls that an administrator has to manage the hotel including adding and deleting rooms.
Image Gallery: This contains image gallery of the rooms in the hotel.
Room Brochure: This is room rate card.
Room Booking History: This is the previous room bookings history stored for future references.
Working:

A new user sign up and creates a new account. Then the user logins using the email and password.
After logging in, user books a room.
The room booking request is sent to hotel administrator. This is the admin job to either confirm or delete the request. User can also delete his/her room booking request if any changes in plan happens.
After the room is confirmed, user will get an option to pay the amount as per the services.
After the user checks out, user will pay the amount and an entry will be made to room booking history.
If any change to plans happens and user opts to extend his stay at the hotel, there is an option available to extend the check out date.
Database file name is iwp.sql. And it is also uploaded.


## Tech
Personal Management System is a web application which can be ran either in Windows and Linux enviroment. Everything is by default tested on Ubuntu 20.x.
Used languages/frameworks/solutions
•	Php 7.4.x
•	MySQL
•	Css
•	And maybe some others which I just don't remember
Used packages
•	EncryptBundle (Core for passwords module)
•	Icon Picker (Icon picker for Notes module)
•	... I don't even know some of them which come prebuild in Symfonator

- [AngularJS] - HTML enhanced for web apps!
- [Ace Editor] - awesome web-based text editor
- [markdown-it] - Markdown parser done right. Fast and easy to extend.
- [Twitter Bootstrap] - great UI boilerplate for modern web apps
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]
- [Gulp] - the streaming build system
- [Breakdance](https://breakdance.github.io/breakdance/) - HTML
to Markdown converter
- [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.
1. Buka XAMPP, jalankan
```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```


## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
