![](Kobo400x400.jpg)

# Welcome Delta Hackers!

In this GitHub repo you can find some resources that could help you make the world a better place for lovers of books.  Build a website that displays book information.  An app that allows users to trade physical books, or one thatfor book lovers to connect. See if you can build a better reading app than Kobo's own! The only limit is your imagination!  We've compiled a list of openly available SDKs, Free and Open Source components and public APIs that are available for you to use for your hacks

If you're curious about some of the things our developers are up to at Rakuten Kobo, you can peruse through our numerous open source projects, on https://github.com/kobolabs.  Some interesting ones to look at:

Some open source components that are used in our Aura ONE eReader: https://github.com/kobolabs/Kobo-Reader
The level of support Kobo has for the ePub Spec: https://github.com/kobolabs/epub-spec
Metadata Quality standards for our Publishers: https://github.com/kobolabs/metadata-style-guide

We've also uploaded a handful of ePub 3 files, along with some relevant data.  You can find them in the eBooks folder in this repository.


## Public APIs

** Internet Archive **
Get information about all kinds of freely available books

https://openlibrary.org/developers/api

** New York Times **

Want to let everyone know what's on the New York Times best seller list? Check out their developer portal. You need to sign up for a key, and it may take an hour or so to get it.  Use this time to use their API explorer to see what data they have to offer!

http://developer.nytimes.com/
http://developer.nytimes.com/books_api.json#/README


** TasteDive.com **

This is a recommendations API that finds similar items to the ones you search for and provides relevant web links to wikipedia.

## ePub Rendering Components

These pieces of software will actually display an ePub file.  These would be most useful, if you're actually looking to build a reading experience.

NOTE: if you plan on "productizing" your hack after this hackathon, pay close attention to the licensing terms for each of these components.  Not all of them may be suitable for commercial use.

**Futurepress Web Epub Viewer**

A JavaScript library for viewing ePub files.  You can find instructions for how to use this component on its GitHub page at https://github.com/futurepress/epub.js/

**React ePub Reader**

A ReactJS wrapper for EPub.js.  https://github.com/gerhardsletten/react-reader

**Readium JS CLoud Viewer**
This is a node.js based component for viewing ePub files on the web.  It is distributed via the NPM package manager.  After installing Node.js and npm, you can install it into your project using 

`npm install readium-js-dist`

Note that this will only work in the Google Chrome web browser. The source code for this component can be found here:

https://github.com

**Readium SDK**

This is a C++ SDK that can be used on Android, iOS and Windows.  
https://github.com/readium/readium-sdk

At one point Kobo used this in some of our reading apps, and you can see our fork on github.com/kobolabs.  Ahh the good old days!

## ePub Reading Components

These are lower level components that can open and parse ePub files, but they aren't able to display them.  You can use these libraries to read (and sometimes write) ePub files.  You could use these libraries to build tools to author ePub files.  This is probably hard given the time, but if you're up for the challenge, see if you can impress us!

**EPubReader**

A .NET library for reading EPUB files.  
https://github.com/vers-one/EpubReader  


