# RED_TETRIS
Tetris Network with Red Pelicans Sauce

# SUMMARY
The objective of this project is to develop a networked multiplayer tetris
game from a stack of software exclusively Full Stack Javascript

# INTRODUCTION
Everyone knows the Tetris Game and everyone knows Javascript, it only remains to build
a Tetris in Javascript.

Yes, but ...
Your Tetris will be multiplayer and online. It will allow you to disturb intergalactic par-
ties during your long coding nights (There are still some WIFI issues on some planets).
Your Tetris will use the latest technologiesJavascriptwhich are at the heart of a great in-
tellectual, industrial and financial battle between Facebook and Google whose challenge
is to be the master of the world.

Your Tetris will require a lot of brain juice to design the architecture, specify an asyn-
chronous network protocol, implemented infunctional programming, create an algorithm
of pieces’ animation and display everything graphically in HTML!

# GENERAL INSTRUCTIONS
The project must be written totally in Javascript and using the latest versions available.
The client code (browser) must be written without a call to "this" in the purpose
of pushing you to use functional constructs and not object. You have the choice of the
functional library (lodash, ramda, ...) to use it or not.

The handling logic of the heap and pieces must be implemented as "pure functions".
An exception to this rule: "this" can be used to define its own subclasses of "Error".
On the opposite, the server code must use object-oriented programming (prototype).
We want to find there at least the Player, Piece and Game classes.
The client application must be built from the React library.

Redux was required before, but due to the evolution of the language, it is recommended
to use React hooks (useContext, useEffect, useMemo), which replace Redux. HTML
code must not use "<TABLE />" elements, but must be built exclusively from a grid or
flexbox layout.

Prohibition to use:

• A DOM manipulation library like jQuery

• Canvas

• SVG (Scalable Vector Graphics)

There is no need to directly manipulate the DOM.

# STEPS TO GET UP AND RUNNING
npm install from client and server directories

enter node_modules in client directory and enter react_scripts directory

inside react_scripts directory enter config directory

open paths.js and edit:

appHtml on line 87 to = appHtml: resolveApp('index.html')

appIndexJs on line 88 to = appIndexJs: resolveModule(resolveApp, 'index')

appSrc on line 90 to = appSrc: resolveApp('')

appPublicon line 86 to = appPublican: resolveApp('')

Everything should run fine after that...
