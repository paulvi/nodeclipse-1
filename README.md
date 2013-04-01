# ATTENSION 

This project possibly doesn't reflect the latest changes.  
Check [Nodeclipse team blog](https://github.com/Nodeclipse/nodeclipse-blog#blog)	

# Nodeclipse - Node.js support in Eclipse IDE

![nodeclipse-logo](nodeclipse-logo-rough.png)

> [Nodeclipse](http://www.nodeclipse.org/) or [Nodeclipse-1 v0.2](http://www.tomotaro1065.com/nodeclipse/) is [Eclipse](http://www.eclipse.org/) plugin for the [Node.js](http://www.nodejs.org/). 
The purpose of Nodeclipse is to create environment in 
which Node.js development is easy for any user from beginner to professional. 

## Vision

One-stop shop for Node.js tools.

We can't develop everything at once, but we let you know what are the best things around for Node.js development with Eclipse.

## Features

* Creating default structure for New Node Project and New Node Source File 
* JavaScript Syntax highlighting
* Content Assistant
* NPM support
* Debugging - Breakpoint, Trace, etc... via [Eclipse debugger plugin for V8](http://code.google.com/p/chromedevtools/)
* Support for Juno

## Installing

Download site v0.1.8: http://www.nodeclipse.org/updates  
Download site v>0.2 (Nodeclipse-1): http://www.tomotaro1065.com/nodeclipse/updates/

## Usage

Check out [great article](http://www.tomotaro1065.com/nodeclipse/) and [watch video](http://tomotaro1065.github.com/nodeclipse/index2.htm).    
For debugging check [Using-Eclipse-as-Node-Applications-Debugger]( https://github.com/joyent/node/wiki/Using-Eclipse-as-Node-Applications-Debugger)

For [Markdown](http://daringfireball.net/projects/markdown/dingus): 

1. Window -> Show View -> Other... -> Markdown
2. Click inside "Markdown HTML Preview" view to refresh rendering
3. (Optional, may be useful because double whitespace is hard line break) 
	Show whitespace character via Preferences > General > Editors > Text Editors : checkbox labeled "Show whitespace characters"


## Roadmap

### 0.3 (April-May 2013)

- Add [Markdown](http://daringfireball.net/projects/markdown/dingus) support via [Markdown Editor plugin for Eclipse]
(http://www.winterwell.com/software/markdown-editor.php) developped by [Daniel Winterstein](http://winterstein.me.uk)  
	Download site: http://winterwell.com/software/updatesite/
- Update template for new project
* Add README.md template
* Add hello-world-server.js
* Add package.json (This is good practice)
v [Publish](http://marketplace.eclipse.org/quickstart) on Eclipse marketplace


### 0.4 (TBD)

TBD

### Ideas, proposals, work-in-progress etc.

- Debugging features without Chrome developer tools.  In other words, debugging on Node Editor
- Obfuscation and source-level debugging features using Source Maps
- Unit test support
- Easily deployment to Heroku (possibly via [Heroku Eclipse plugin](https://devcenter.heroku.com/articles/getting-started-with-heroku-eclipse))  
	Download site: https://eclipse-plugin.herokuapp.com/install

- Add [JSHint](http://www.jshint.com/) integration for Eclipse, [developed by EclipseSource](https://github.com/eclipsesource/jshint-eclipse)  
	Download site: http://github.eclipsesource.com/jshint-eclipse/updates/
- Add Jade support	(http://blog.wookets.com/2011/10/how-to-compile-coffeescript-jade-stylus.html Posted 30th October 2011 by Sean Wesenberg)
- Integrate console window (library unknown)
- Add CoffeeScript support via [coffeescript-eclipse plugin](https://github.com/adamschmideg/coffeescript-eclipse)  
	Download site: http://coffeescript-editor.eclipselabs.org.codespot.com/hg/
- [Eclipse Json Editor Plugin](http://sourceforge.net/p/eclipsejsonedit/wiki/Home/) Last Update: 2012-11-07
 (The JSON Editor is a simple plugin for the Eclipse IDE that provides: - Color text highlighting - An Outline Tree view - JSON validation
  - Text formatting - Text folding for the JSON data format.)	
  No Update site.
	
## Developing

Before starting development, please do

1. Carefully read materials
2. Install and give thorough try
3. Contact developers, make friends
4. Say what you are going to do, before you head in. Share and discuss ideas.

## Contributors
LambGao 魔都 https://github.com/Nodeclipse (original creator v0.1.8)   
Scott Elcomb https://github.com/psema4  
Tomoyuki Inagaki https://github.com/tomotaro1065 (debugging integration v0.2) [blog](http://d.hatena.ne.jp/tomotaro1065/)   
Paul Verest https://github.com/PaulVI/  (Vision, readme, reference to plugings) [blog](https://github.com/PaulVI/blog)   

## Contacts
Do not hesitate to contact developers. 
Create issue or send [email to dev group](mailto:dev@nodeclipse.org).
Or skype me by ID pverest, QQ 908781544.

## For Bloggers and Users of Twitter, Flickr, LinkedIn, Weibo etc.

In case you plan to blog or tweet about the Nodeclipse plugin, please use the tag "#nodeclipse"
 in order to make it easier to find all the comments and pictures. Thanks a lot for telling the world about the project!  
  | 请用#nodeclipse#标签微博一下。  
  | Por favor, utilizar etiqueta #nodeclipse  
  | ツイートする時は、＃nodeclipseタグを使用してください。  
  | Bitte benutzen Sie tag #nodeclipse um zu twiten.


## Spread the words

Please let others know about this effort. Add links below:  

Sites that reference this project  
http://www.oschina.net/p/nodeclipse  
http://stackoverflow.com/questions/8025825/is-there-a-nodejs-plugin-for-aptana-studio  
http://stackoverflow.com/questions/8179369/debugging-node-js-with-eclipse  
http://stackoverflow.com/questions/7038961/node-js-in-eclipse-which-plugins-are-most-people-using  
https://groups.google.com/forum/#!msg/nodejs/ayLUeUOanzA/et6EEZppVjMJ  
http://stackoverflow.com/questions/15407334/eclipse-rcp-add-optional-dependencies  
http://cnodejs.org/topic/5149c795069911196df84af7 
http://en.wikipedia.org/wiki/List_of_Eclipse_projects#Third_party_projects
http://stackoverflow.com/questions/2353818/how-do-i-get-started-with-node-js/15700606#15700606  
http://stackoverflow.com/questions/609316/debug-javascript-in-eclipse/15701220

### Hot requests

http://stackoverflow.com/questions/14533885/which-ide-supports-coffeescript-debugging-source-mapping-breakpoints-call-st  
http://stackoverflow.com/questions/10286364/coffeescript-editor-plugin-for-eclipse  
http://stackoverflow.com/questions/7057466/how-to-use-coffeescript-and-eclipse-together-in-windows  
http://stackoverflow.com/questions/3919977/what-ide-to-use-for-node-js-javascript asked Oct 13 '10 [closed] -> Vim, Cloud9 IDE, editors
http://www.iteye.com/news/23933        

### Interesting and useful Links

#### Other Node IDEs

Nide http://coreh.github.com/nide/ v0.2 Last update 2012-04  
JetBrains WebStorm or [IntelliJ IDEA](www.jetbrains.com/idea/features/nodejs.html) (commercial products)  
Microsoft WebMatrix (free) or Visual Studio (commercial product)  
CloudIDE [c9.io](https://c9.io) (cloud service)  
Scripted https://github.com/scripted-editor/scripted  
Eclipse Orion  
komodo-ide http://www.activestate.com/komodo-ide (commercial product)  
Netbeans have a [NodeJS plugin](http://plugins.netbeans.org/plugin/36653/nodejs)  

#### Hints

http://wiki.eclipse.org/Tycho/Reference_Card  
http://stackoverflow.com/questions/10352089/how-do-i-build-an-eclipse-rcp-app-so-that-its-features-can-be-updated-automatica?rq=1  
http://stackoverflow.com/questions/14591472/installing-an-additional-feature-during-product-build-for-some-eclipse-versions  
http://stackoverflow.com/questions/10529859/how-to-include-video-in-jekyll-markdown-blog  
http://stackoverflow.com/questions/2330620/eclipse-i-turned-on-hidden-characters-now-i-cant-turn-off  
[Eclipse JavaScript Development Tools (JSDT)](http://eclipse.org/webtools/jsdt/) has only JS web support.
http://stackoverflow.com/questions/300855/looking-for-a-better-javascript-unit-test-tool  
http://stackoverflow.com/questions/4025444/eclipse-javascript-editor-10   
add interesting stuff here...

