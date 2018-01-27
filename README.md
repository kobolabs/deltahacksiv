# Welcome Delta Hackers!

In this GitHub repo you can find some insipiration for how you could make the world a better place for lovers of books.  We've compiled a list of openly available SDKs, Free and Open Source components and public APIs that are available for you to use for your hacks

If you're curious about the type of work done at Rakuten Kobo, you can peruse through our numerous open source projects, on https://github.com/kobolabs

## ePub Rendering Components

These pieces of software will actually display an ePub file.

NOTE: if you plan on "productizing" your hack after this hackathon, pay close attention to the licensing terms for each of these components.  Not all of them may be suitable for commercial use.

**Futurepress Web Epub Viewer**

A JavaScript library for viewing ePub files.  You can find instructions for how to use this component on its GitHub page at https://github.com/futurepress/epub.js/

**Readium JS CLoud Viewer**
This is a node.js based component for viewing ePub files.  It is distributed via the NPM package manager.  After installing Node.js and npm, you can install it into your project using 

`npm install readium-js-dist`

Note that this will only work in the Google Chrome web browser.

## ePub Reading Components

These components can open and parse ePub files, but they aren't able to display them.  You can use these libraries to parse an epub file. 

**EPubReader**

A .NET library for reading EPUB files.  If you are familiar with Xamarin development, you could potentially use this component to build an app that targets iOS and Android
https://github.com/vers-one/EpubReader

