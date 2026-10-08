# personal website

It's a personal website of small size in which I record the things I'm working on, the things I'm learning about, and the things I'm building.

it's essentially just a collection of my projects, hobbies, and the various things I'm experimenting with.

## what's on the site

### things i'm interested in

* stock prediction AI
* local AI devices
* computer architecture
* hardware efficiency
* AI and systems

### projects

* smart parking system
* smoke detector
* breadboard console
* simple antivirus
* trading terminal

There is a separate section for each project, containing a brief description and, when necessary, some links or screenshots.

## how it works

The site uses plain HTML and CSS.

There is neither any framework nor any build toolbut  instead, the various sections navigate to one another using URL hashes, the CSS being responsible for determining which section is displayed.

For example like 

index.html#trading-terminal

index.html#breadboard-console

index.html#antivirus

## project structure


├── index.html
└── images/
    ├── trading-marketwatch.png
    ├── trading-positions.png
    └── trading-world-map.png

The index.html file contains both the main page and its CSS.

The screenshots used in the trading terminal section are stored in the `images` folder.

## running it

You don't need to carry out any installation or build process.

All you have to do is open the file index.html in a browser.

You can also run it with a simple static server like for example:

python -m http.server

## hosting

The website is hosted on Vercel too 

https://personal-site-delta-amber.vercel.app/

## current status

It is almost done i mainly built this project for https://stardance.hackclub.com
