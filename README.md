# Static playground

<img src="https://user-images.githubusercontent.com/589285/129468656-db58c34c-d92b-4f51-ba4d-cb6417c64de5.gif" alt="Preview of the playground" width="1280">

A boilerplate including **hot-reload** to prototype **static websites** with a minimal footprint. It comes with:

- A webserver with hot-reload
- An external server: test your site on mobile and other devices
- Real-time synchronization between connected devices
- Remote web inspector tools to debug from the different connected devices
- Support for HTML, CSS, JS and other static files

## Installation and Usage

To start using it simply clone this repository and run the following commands on your terminal:

```
npm install
npm start
```

It will automatically start a local server at `http://localhost:3000`. You can customize what files are watched and other options in `res/bs-config.js`.

If you visit `http://localhost:3001`, you will see a dashboard to customize other options from [Browsersync](https://browsersync.io).

There's also an external server at `http://<your-ip>:3001` that you can use to test your website directly from other devices sharing the same network. This is great to quickly test things on your phone with hot-reload as well as syncronized scrolling.

## Beyond the basics

Although it's not part of this boilerplate, you can grow the functionality by combining it with [gulp](https://browsersync.io/docs/gulp), and start supporting `SCSS` and other things you may need.

## License

The tool is available as open-source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
