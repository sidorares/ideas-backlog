ideas-backlog
=============

I have long list of 'just ideas' or projects I started but unlikely finish soon. I'll put all metadata (mostly links explaining related technology) here. Feel free to implement idea or finish project. Ping me if you know someone already doing it or if you start something related.


### node wrapper for [tomita parser](http://api.yandex.ru/tomita/doc/tutorial/concept/about.xml)
  - http://habrahabr.ru/company/yandex/blog/219311/
  - http://habrahabr.ru/company/yandex/blog/184788/

### Atom.io package: 'Go to line' with support for sourcemaps 

### [Sikuli](http://www.sikuli.org/)-like testing framework, but implemented in node (and thus supporting non-linear/parallel/evented flow). Also uses [rfb](https://github.com/sidorares/node-rfb2) client to interact with test host so should be able to connect to any system with vnc server.
  - need to port MatchTemplate to js or use opencv bindings
  - http://stackoverflow.com/questions/9709631/how-do-i-use-opencv-matchtemplate-how-exactly-does-it-work
  - http://opencv-code.com/tutorials/fast-template-matching-with-image-pyramid/
  - Tesseract bindings for node:
    - https://github.com/estliberitas/node-tesseract
    - https://github.com/jmealo/node-tesseract-ocr
    - https://github.com/desmondmorris/node-tesseract
    
### X11 composite manager in node using node-x11
  - http://www.talisman.org/~erlkonig/misc/x11-composite-tutorial/
  - ideally need to get [ARB shaders](https://github.com/sidorares/node-x11/issues/50) and [BindTexImage](https://github.com/sidorares/node-x11/issues/52) in node-x11 to work, but double using Render only 
  
### [i3](http://i3wm.org/)-like window manager in js
  - https://github.com/dominictarr/tiles
  - https://github.com/sidorares/node-x11/tree/master/examples/windowmanager

### XSettings manager using [node-x11](https://github.com/sidorares/node-x11)
  - http://kevinboone.net/xdesktop_other.html
  - http://code.metager.de/source/xref/freedesktop/xdg/specs/xsettings/settings-proposal.txt
 
### [Pango](http://www.pango.org/) node bindings
  - finish implementing [render-glyphs](https://github.com/sidorares/node-x11/pull/61)
  - use pango directly with node-x11 & RenderCompositeGlyph
  - [HarfBuzz](http://www.freedesktop.org/wiki/Software/HarfBuzz/) bindings?

### Static blog/CMS: Reuse md editor from [ghost](https://ghost.org/), save everything to github repo, publish to gh-pages. All comminucation to github via github api and in-browser git client. Login also via github

### node.js debugger protocol multiplexer (similar to [crmux](https://github.com/sidorares/crmux) but for V8 protocol)

### [Berkley Packet Filter](http://en.wikipedia.org/wiki/Berkeley_Packet_Filter) assembly to JavaScript compiler
  - API: compile(assembly) -> JS function. (buffer, offet) -> accepted offset
  - https://github.com/netsniff-ng/netsniff-ng/blob/master/bpf.c
  - http://www.gsp.com/cgi-bin/man.cgi?topic=bpf
  - https://www.kernel.org/doc/Documentation/networking/filter.txt
  
### credit card polymer element
  - http://customelements.io/
  - https://github.com/kenkeiter/skeuocard
  - https://github.com/webcomponents/element-boilerplate
  
### proper lexer-based sourcemaps generation for stylus
  - https://github.com/LearnBoost/stylus/pull/1129
  - https://github.com/LearnBoost/stylus/pull/1427
  - https://coderwall.com/p/bhtxkq

### proper lexer-based sourcemaps generation for [jade](https://github.com/sidorares/browserify-jade)
  - https://github.com/sidorares/browserify-jade

### asm.js JIT compiler for node using [jit.js](https://github.com/indutny/jit.js)
  - also: dynamically generate machine code to read mysql rows in (mysql2)[https://github.com/sidorares/node-mysql2]

