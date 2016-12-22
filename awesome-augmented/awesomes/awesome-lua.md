<h1>
 Awesome Lua
 <a href="https://github.com/sindresorhus/awesome">
  <img alt="Awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg"/>
 </a>
</h1>
<blockquote>
 <p>
  A curated list of quality Lua
  <a href="#packages">
   packages
  </a>
  and
  <a href="#resources">
   resources
  </a>
  .
 </p>
</blockquote>
<p>
 Inspired by the lists
 <a href="https://github.com/sindresorhus/awesome">
  awesome
 </a>
 ,
 <a href="https://github.com/bayandin/awesome-awesomeness">
  awesome-awesomeness
 </a>
 , and
 <a href="https://github.com/sindresorhus/awesome-nodejs">
  awesome-nodejs
 </a>
 .
</p>
<h2>
 Packages
</h2>
<ul>
 <li>
  <a href="#implementations-interpreters-and-bindings">
   Implementations, Interpreters, and Bindings
  </a>
 </li>
 <li>
  <a href="#package-managers">
   Package Managers
  </a>
 </li>
 <li>
  <a href="#debugging-and-profiling">
   Debugging and Profiling
  </a>
 </li>
 <li>
  <a href="#ides-and-plugins">
   IDEs and Plugins
  </a>
 </li>
 <li>
  <a href="#utility-belts">
   Utility Belts
  </a>
 </li>
 <li>
  <a href="#game-engines">
   Game Engines
  </a>
 </li>
 <li>
  <a href="#game-development">
   Game Development
  </a>
 </li>
 <li>
  <a href="#logging">
   Logging
  </a>
 </li>
 <li>
  <a href="#webnetworking-platforms">
   Web/Networking Platforms
  </a>
 </li>
 <li>
  <a href="#openresty">
   OpenResty
  </a>
 </li>
 <li>
  <a href="#command-line-utilities">
   Command-line Utilities
  </a>
 </li>
 <li>
  <a href="#concurrency-and-multithreading">
   Concurrency and Multithreading
  </a>
 </li>
 <li>
  <a href="#templating">
   Templating
  </a>
 </li>
 <li>
  <a href="#documentation">
   Documentation
  </a>
 </li>
 <li>
  <a href="#object-oriented-programming">
   Object-oriented Programming
  </a>
 </li>
 <li>
  <a href="#filesystem-and-os">
   Filesystem and OS
  </a>
 </li>
 <li>
  <a href="#time-and-date">
   Time and Date
  </a>
 </li>
 <li>
  <a href="#image-manipulation">
   Image Manipulation
  </a>
 </li>
 <li>
  <a href="#digital-signal-processing">
   Digital Signal Processing
  </a>
 </li>
 <li>
  <a href="### hardware-and-embedded-systems">
   Hardware and Embedded Systems
  </a>
 </li>
 <li>
  <a href="#math-and-scientific-computing">
   Math and Scientific Computing
  </a>
 </li>
 <li>
  <a href="#parsing">
   Parsing
  </a>
 </li>
 <li>
  <a href="#humanize">
   Humanize
  </a>
 </li>
 <li>
  <a href="#compression">
   Compression
  </a>
 </li>
 <li>
  <a href="#cryptography">
   Cryptography
  </a>
 </li>
 <li>
  <a href="#network">
   Network
  </a>
 </li>
 <li>
  <a href="#data-stores">
   Data Stores
  </a>
 </li>
 <li>
  <a href="#testing">
   Testing
  </a>
 </li>
 <li>
  <a href="#foreign-function-interfaces">
   Foreign Function Interfaces
  </a>
 </li>
 <li>
  <a href="#analysis-tools-and-asts">
   Analysis Tools and ASTs
  </a>
 </li>
 <li>
  <a href="#experimental-etc">
   Experimental, etc
  </a>
 </li>
 <li>
  <a href="#scriptable-by-lua">
   Scriptable by Lua
  </a>
 </li>
 <li>
  <a href="#miscellaneous">
   Miscellaneous
  </a>
 </li>
</ul>
<h2>
 Resources
</h2>
<ul>
 <li>
  <a href="#references">
   References
  </a>
 </li>
 <li>
  <a href="#style-guides">
   Style Guides
  </a>
 </li>
 <li>
  <a href="#tutorials">
   Tutorials
  </a>
 </li>
 <li>
  <a href="#articles">
   Articles
  </a>
 </li>
 <li>
  <a href="#talks--slides">
   Talks & Slides
  </a>
 </li>
 <li>
  <a href="#books">
   Books
  </a>
 </li>
 <li>
  <a href="#other-lists">
   Other Lists
  </a>
 </li>
</ul>
<h3>
 Implementations, Interpreters, and Bindings
</h3>
<ul>
 <li>
  <a href="http://www.lua.org/download.html">
   Lua
  </a>
  - Lua's original ANSI C interpreter.
 </li>
 <li>
  <a href="http://luajit.org/luajit.html">
   LuaJIT
  </a>
  - High-performance Just-In-Time compiler for Lua.
 </li>
 <li>
  <a href="https://github.com/neopallium/llvm-lua">
   LLVM-Lua
  </a>
  - Compiles Lua to LLVM.
  <sup>
   &#9733 1, pushed 109 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/kripken/lua.vm.js">
   lua.vm.js
  </a>
  - Lua VM on the web; a direct port of the C interpreter via LLVM, emscripten, and asm.js.
  <sup>
   &#9733 538, pushed 21 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/gamesys/moonshine">
   Moonshine
  </a>
  - A Lua VM implemented in JavaScript. Slower than lua.vm.js, but with better docs, examples, and JS interfacing.
  <sup>
   &#9733 336, pushed 63 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/xanathar/moonsharp">
   MoonSharp
  </a>
  - A Lua interpreter written entirely in C# for the .NET, Mono and Unity platforms.
  <sup>
   &#9733 210, pushed 40 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/xebecnan/UniLua">
   UniLua
  </a>
  - A pure C# implementation of Lua 5.2, focused on compatibility with the Unity game engine.
  <sup>
   &#9733 672, pushed 345 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/scoder/lupa">
   lupa
  </a>
  - Python bindings to LuaJIT2.
  <sup>
   &#9733 293, pushed 21 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/aarzilli/golua">
   golua
  </a>
  - Golang bindings to the Lua C API.
  <sup>
   &#9733 268, pushed 26 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/yuin/gopher-lua">
   GopherLua
  </a>
  - Lua 5.1 VM and compiler implemented in Go with Go APIs.
  <sup>
   &#9733 1170, pushed 8 days ago
  </sup>
 </li>
</ul>
<p>
 Note: From LuaJIT to Lua to lua.vm.js to Moonshine, a basic benchmark sees performance drop by roughly a factor of 6 with each hop.
</p>
<h3>
 Package Managers
</h3>
<ul>
 <li>
  <a href="http://luarocks.org/en">
   LuaRocks
  </a>
  - Allows you to install Lua modules as packages called "rocks", which contain version and dependency information. Much like npm or pip.
 </li>
 <li>
  <a href="https://rocks.moonscript.org/">
   MoonRocks
  </a>
  - Public Lua rock repository, website, and uploading tool. Default server used by LuaRocks.
 </li>
</ul>
<h3>
 Debugging and Profiling
</h3>
<ul>
 <li>
  <a href="https://gist.github.com/perky/2838755">
   ProFi
  </a>
  - Simple profiler that works with LuaJIT and produces a report file.
 </li>
 <li>
  <a href="https://github.com/geoffleyland/luatrace">
   luatrace
  </a>
  - Toolset for tracing/analyzing/profiling script execution and generating detailed reports.
  <sup>
   &#9733 93, pushed 155 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/ignacio/StackTracePlus">
   StackTracePlus
  </a>
  - Drop-in upgrade to Lua's stack traces which adds local context and improves readability.
  <sup>
   &#9733 108, pushed 77 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/pkulchenko/MobDebug">
   MobDebug
  </a>
  - Powerful remote debugger with breakpoints and stack inspection. Used by ZeroBraneStudio.
  <sup>
   &#9733 235, pushed 51 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/rxi/lovebird">
   lovebird
  </a>
  - Browser-based debug console. Originally made for LÖVE, but works in any project with LuaSocket support.
  <sup>
   &#9733 89, pushed 233 days ago
  </sup>
 </li>
</ul>
<h3>
 IDEs and Plugins
</h3>
<ul>
 <li>
  <a href="http://www.eclipse.org/koneki/ldt/">
   Lua Development Tools
  </a>
  - Eclipse plugin which provides code completion, debugging, and more. Built on Metalua.
 </li>
 <li>
  <a href="https://bitbucket.org/sylvanaar2/lua-for-idea/wiki/Home">
   Lua for IDEA
  </a>
  - IntelliJ IDEA plugin which, among other things, provides code completion, smart highlighting, and experimental debugging.
 </li>
 <li>
  <a href="http://studio.zerobrane.com/">
   ZeroBraneStudio
  </a>
  - Lightweight, customizable, cross-platform Lua-dedicated IDE with code completion and analysis, written in Lua. Has broad debugging support for numerous Lua engines.
 </li>
 <li>
  <a href="http://babelua.codeplex.com/">
   Babelua
  </a>
  - Lua editor/debugger, extension for Visual Studio 2012/2013. Has code highlight, auto-completion, syntax checking and formatting, file previewing, debugging capabilities integrated into Visual Studio.
 </li>
</ul>
<h3>
 Utility Belts
</h3>
<ul>
 <li>
  <a href="https://github.com/rtsisyk/luafun">
   Lua Fun
  </a>
  - High-performance functional programming library designed for LuaJIT.
  <sup>
   &#9733 827, pushed 42 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/Yonaba/Moses">
   Moses
  </a>
  - Functional programming utility belt, inspired by Underscore.js.
  <sup>
   &#9733 247, pushed 87 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/stevedonovan/Penlight">
   Penlight
  </a>
  - Broad, heavyweight utility library, inspired by Python's standard libs. Provides the batteries that Lua doesn't.
  <sup>
   &#9733 534, pushed 1 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/lua-stdlib/lua-stdlib">
   lua-stdlib
  </a>
  - Middle-weight standard library extension; adds some useful data structures, utility functions, and basic functional stuff.
  <sup>
   &#9733 127, pushed 88 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/stevedonovan/Microlight">
   Microlight
  </a>
  - A little library of useful Lua functions; the 'extra light' version of Penlight.
  <sup>
   &#9733 73, pushed 55 days ago
  </sup>
 </li>
</ul>
<h3>
 Game Engines
</h3>
<ul>
 <li>
  <a href="http://love2d.org/">
   LÖVE 2D
  </a>
  - Desktop game development platform. Cross-platform, feature-complete, well-adopted.
 </li>
 <li>
  <a href="https://coronalabs.com/products/corona-sdk/">
   Corona SDK
  </a>
  - Development platform for iOS and Android. Proprietary, but used by numerous top games and apps, totaling over 150 million downloads.
 </li>
 <li>
  <a href="http://getmoai.com/">
   MOAI
  </a>
  - Open source, cross-platform, mobile game development framework. Minimalist C++ engine powered by Lua scripting.
 </li>
 <li>
  <a href="https://drystal.github.io/">
   Drystal
  </a>
  - Open source, games can run on Linux or on any platform with a recent web browser.
 </li>
 <li>
  <a href="http://www.amulet.xyz/">
   Amulet
  </a>
  - Open source, audio/visual toolkit suitable for small games and experimentation. It runs on Windows, Mac, Linux, HTML5 and iOS.
 </li>
 <li>
  <a href="https://gengine.bitballoon.com/">
   gengine
  </a>
  - A 2d game engine for fast development, using entities and components system, for Linux, Windows and HTML5.
 </li>
</ul>
<h3>
 Game Development
</h3>
<ul>
 <li>
  Corona
  <ul>
   <li>
    <a href="http://coronium.io/">
     Coronium.io
    </a>
    - Simple cloud platform supporting analytics, data objects, user management, and more.
   </li>
  </ul>
 </li>
 <li>
  LÖVE
  <ul>
   <li>
    <a href="https://github.com/JanWerder/awesome-love2d">
     awesome-love2d
    </a>
    - A list like this one, but focused on game dev and the LÖVE platform.
   </li>
   <li>
    <a href="https://github.com/rxi/lurker">
     lurker
    </a>
    - Shortens the iteration cycle by auto-swapping changed Lua files in a running LÖVE project.
    <sup>
     &#9733 66, pushed 426 days ago
    </sup>
   </li>
   <li>
    <a href="http://vrld.github.io/hump">
     HUMP
    </a>
    - A set of lightweight helpers for LÖVE; a game-oriented utility belt.
   </li>
  </ul>
 </li>
 <li>
  MOAI
  <ul>
   <li>
    <a href="http://moaifiddle.com">
     moaifiddle
    </a>
    - Edit and share short scripts for the MOAI game engine and run them in the browser using WebGL.
   </li>
  </ul>
 </li>
 <li>
  <a href="https://github.com/Yonaba/Jumper">
   Jumper
  </a>
  - Fast, lightweight, and easy-to-use pathfinding library for grid-based games.
  <sup>
   &#9733 312, pushed 35 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/rxi/lume/">
   lume
  </a>
  - Utility belt library geared toward game development.
 </li>
 <li>
  <a href="https://github.com/Overtorment/NoobHub">
   NoobHub
  </a>
  - Network multiplayer for Corona, LÖVE, and more, following a simple pub-sub model.
  <sup>
   &#9733 122, pushed 204 days ago
  </sup>
 </li>
 <li>
  Collision detection
  <ul>
   <li>
    <a href="https://github.com/kikito/bump.lua">
     bump.lua
    </a>
    - Minimal rectangle-based collision detection which handles tunnelling and basic collision resolution.
   </li>
   <li>
    <a href="http://vrld.github.io/HardonCollider/">
     HardonCollider
    </a>
    - Detect collisions between arbitrarily positioned and rotated shapes of any type.
   </li>
  </ul>
  <sup>
   &#9733 210, pushed 79 days ago
  </sup>
 </li>
 <li>
  Tweening
  <ul>
   <li>
    <a href="https://github.com/rxi/flux">
     flux
    </a>
    - A fast, lightweight tweening library for Lua with easing functions and the ability to group tweens together.
   </li>
   <li>
    <a href="https://github.com/kikito/tween.lua">
     tween.lua
    </a>
    - Small library for tweening, with several easing functions.
    <sup>
     &#9733 195, pushed 41 days ago
    </sup>
   </li>
  </ul>
  <sup>
   &#9733 78, pushed 38 days ago
  </sup>
 </li>
 <li>
  Examples
  <ul>
   <li>
    <a href="https://github.com/tylerneylon/termtris">
     termtris
    </a>
    - A tetris clone, written in literate style with "an emphasis on learn-from-ability".
   </li>
   <li>
    <a href="https://github.com/tylerneylon/pacpac">
     PacPac
    </a>
    - A Pac-man clone, made with LÖVE.
    <sup>
     &#9733 305, pushed 320 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/Stabyourself/mari0">
     Mari0
    </a>
    - Fusion of Mario and Portal, made with LÖVE. See also its
    <a href="https://en.wikipedia.org/wiki/Mari0">
     wikipedia entry
    </a>
    .
    <sup>
     &#9733 126, pushed 7 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/hawkthorne/hawkthorne-journey">
     Journey to the Center of Hawkthorne
    </a>
    - 2D platformer based on Community's
    <a href="https://en.wikipedia.org/wiki/Digital_Estate_Planning">
     Digital Estate Planning
    </a>
    episode, made with LÖVE.
    <sup>
     &#9733 715, pushed 40 days ago
    </sup>
   </li>
  </ul>
  <sup>
   &#9733 393, pushed 571 days ago
  </sup>
 </li>
</ul>
<h3>
 Logging
</h3>
<ul>
 <li>
  <a href="https://github.com/moteus/lua-log">
   log-lua
  </a>
  - Asynchronous logging library with pluggable writers for filesystem, network, ZeroMQ, and more.
  <sup>
   &#9733 42, pushed 124 days ago
  </sup>
 </li>
</ul>
<h3>
 Web/Networking Platforms
</h3>
<ul>
 <li>
  <a href="http://openresty.org/">
   OpenResty
  </a>
  - A fast and scalable web application platform created by extending Nginx with Lua. Today's de-facto Lua web platform, used heavily by Cloudflare, Taobao, Tencent, and others.
 </li>
 <li>
  <a href="http://www.turbolua.org/">
   turbo
  </a>
  - Event-driven, non-blocking, LuaJIT-based networking suite and framework, inspired by Tornado.
 </li>
 <li>
  <a href="http://www.keplerproject.org/">
   Kepler Project
  </a>
  - A collection of web-oriented projects using a common set of standards and components.
 </li>
 <li>
  <a href="http://github.com/EvandroLG/pegasus.lua">
   Pegasus.lua
  </a>
  - Pegasus.lua is a http server to work with web applications written in Lua language.
 </li>
</ul>
<h3>
 OpenResty
</h3>
<ul>
 <li>
  <a href="https://github.com/bungle/awesome-resty">
   awesome-resty
  </a>
  - A list like this one, but focused on OpenResty.
  <sup>
   &#9733 319, pushed 4 days ago
  </sup>
 </li>
 <li>
  Core platform
  <ul>
   <li>
    <a href="https://www.nginx.com/resources/wiki/modules/lua/">
     ngx_lua
    </a>
    - The core piece of OpenResty. Embeds Lua in Nginx and exposes, among other things, the cosocket API for non-blocking sockets (compatible with LuaSocket's API).
   </li>
   <li>
    <a href="https://github.com/openresty">
     OpenResty GitHub Organization
    </a>
    - Home of the repositories for ngx
    <em>
     lua, ngx
    </em>
    openresty, and many related modules.
   </li>
  </ul>
 </li>
 <li>
  Third-party modules
  <ul>
   <li>
    <a href="https://github.com/pintsized/lua-resty-http">
     lua-resty-http
    </a>
    - Lua HTTP client driver, built on the cosocket API.
   </li>
  </ul>
  <sup>
   &#9733 261, pushed 4 days ago
  </sup>
 </li>
 <li>
  Frameworks & tools
  <ul>
   <li>
    <a href="http://leafo.net/lapis/">
     Lapis
    </a>
    - Full-stack framework for Lua and OpenResty. Like the Django or Rails of Lua. Supports Moonscript.
   </li>
   <li>
    <a href="https://github.com/pintsized/ledge">
     ledge
    </a>
    - Lua module providing scriptable, RFC-compliant HTTP cache functionality.
    <sup>
     &#9733 199, pushed 41 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/sailorproject/sailor">
     Sailor
    </a>
    — An MVC web framework compatible with OpenResty, Apache and other webservers.
    <sup>
     &#9733 594, pushed 3 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/mashape/kong">
     Kong
    </a>
    - Microservice & API Management Layer
    <sup>
     &#9733 5107, pushed 2 days ago
    </sup>
   </li>
  </ul>
 </li>
</ul>
<p>
 Search this page for 'OpenResty' to find related packages under other categories (data stores in particular).
</p>
<h3>
 Command-line Utilities
</h3>
<ul>
 <li>
  <a href="https://github.com/kikito/ansicolors.lua">
   ansicolors
  </a>
  - Simple function for printing to the console in color.
  <sup>
   &#9733 37, pushed 346 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/amireh/lua_cliargs">
   cliargs
  </a>
  - A simple command-line argument parsing module.
  <sup>
   &#9733 39, pushed 112 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/hoelzro/lua-term">
   lua-term
  </a>
  - Terminal operations and manipulations.
  <sup>
   &#9733 45, pushed 28 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/mpeterv/argparse">
   argparse
  </a>
  - A feature-rich command line parser inspired by argparse for Python.
  <sup>
   &#9733 56, pushed 103 days ago
  </sup>
 </li>
</ul>
<h3>
 Concurrency and Multithreading
</h3>
<ul>
 <li>
  Coroutine-based multitasking:
  <ul>
   <li>
    <a href="https://github.com/xopxe/Lumen">
     Lumen
    </a>
    - Simple concurrent task scheduling.
   </li>
   <li>
    <a href="https://github.com/lefcha/concurrentlua">
     ConcurrentLua
    </a>
    - Implements an Erlang-style message-passing concurrency model.
    <sup>
     &#9733 132, pushed 528 days ago
    </sup>
   </li>
  </ul>
  <sup>
   &#9733 79, pushed 29 days ago
  </sup>
 </li>
 <li>
  Multithreading:
  <ul>
   <li>
    <a href="https://github.com/Neopallium/lua-llthreads">
     llthreads
    </a>
    - A simple wrapper for low-level pthreads & WIN32 threads.
   </li>
   <li>
    <a href="https://github.com/LuaLanes/lanes">
     lanes
    </a>
    - Library implementing a message passing model with one OS thread per Lua thread.
    <sup>
     &#9733 171, pushed 13 days ago
    </sup>
   </li>
   <li>
    <a href="https://github.com/askyrme/luaproc">
     luaproc
    </a>
    - Message-passing model which allows multiple threads per OS thread and easily generalizes across a network. See also
    <a href="http://www.inf.puc-rio.br/~roberto/docs/ry08-05.pdf">
     the paper
    </a>
    where it originated.
    <sup>
     &#9733 60, pushed 32 days ago
    </sup>
   </li>
  </ul>
  <sup>
   &#9733 100, pushed 102 days ago
  </sup>
 </li>
</ul>
<p>
 For more on the differences (particularly between
 <code>
  lanes
 </code>
 and
 <code>
  luaproc
 </code>
 ), see this
 <a href="http://cmr.github.io/lanes/comparison.html">
  comparison
 </a>
 of options; somewhat dated, but covers how each one works and the significant differences.
</p>
<h3>
 Templating
</h3>
<ul>
 <li>
  <a href="http://olivinelabs.com/lustache/">
   lustache
  </a>
  - Mustache template implementation.
 </li>
 <li>
  <a href="https://github.com/leafo/etlua">
   etlua
  </a>
  - Embedded Lua templates, ERB-style.
  <sup>
   &#9733 74, pushed 804 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/bungle/lua-resty-template">
   lua-resty-template
  </a>
  - Lua-oriented template engine for OpenResty, somewhat Jinja-like.
  <sup>
   &#9733 261, pushed 7 days ago
  </sup>
 </li>
</ul>
<h3>
 Documentation
</h3>
<ul>
 <li>
  <a href="http://stevedonovan.github.io/ldoc/">
   LDoc
  </a>
  - Documentation generator which modernizes and extends
  <a href="http://keplerproject.github.io/luadoc/">
   LuaDoc
  </a>
  .
 </li>
 <li>
  <a href="http://rgieseke.github.io/locco/">
   Locco
  </a>
  - Lua port of
  <a href="http://jashkenas.github.io/docco/">
   Docco
  </a>
  , the "quick-and-dirty, hundred-line-long, literate-programming-style documentation generator".
 </li>
 <li>
  <a href="https://github.com/bjornbytes/docroc">
   docroc
  </a>
  - Parse comments into a Lua table to generate documentation.
  <sup>
   &#9733 3, pushed 130 days ago
  </sup>
 </li>
</ul>
<h3>
 Object-oriented Programming
</h3>
<ul>
 <li>
  <a href="https://github.com/Yonaba/30log">
   30log
  </a>
  - Minimalist OOP library with basic classes, inheritance, and mixins in 30 lines.
  <sup>
   &#9733 174, pushed 58 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/kikito/middleclass">
   middleclass
  </a>
  - Simple but robust OOP library with inheritance, methods, metamethods, class variables and mixins.
  <sup>
   &#9733 659, pushed 44 days ago
  </sup>
 </li>
</ul>
<h3>
 Filesystem and OS
</h3>
<ul>
 <li>
  <a href="http://keplerproject.github.io/luafilesystem/">
   LuaFileSystem
  </a>
  - Extends and complements Lua's built-in set of filesystem functions.
 </li>
 <li>
  <a href="https://github.com/luaposix/luaposix">
   luaposix
  </a>
  - Bindings for POSIX APIs, including curses.
  <sup>
   &#9733 192, pushed 24 days ago
  </sup>
 </li>
</ul>
<h3>
 Time and Date
</h3>
<ul>
 <li>
  <a href="https://github.com/Tieske/date">
   LuaDate
  </a>
  - Date and time module with parsing, formatting, addition/subtraction, localization, and ISO 8601 support.
  <sup>
   &#9733 66, pushed 173 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/kikito/cron.lua">
   cron.lua
  </a>
  - Time-related functions for Lua, inspired by JavaScript's setTimeout and setInterval.
  <sup>
   &#9733 70, pushed 932 days ago
  </sup>
 </li>
</ul>
<h3>
 Image Manipulation
</h3>
<ul>
 <li>
  <a href="https://github.com/leafo/magick">
   magick
  </a>
  - Lua bindings to ImageMagick for LuaJIT using FFI.
  <sup>
   &#9733 163, pushed 63 days ago
  </sup>
 </li>
</ul>
<h3>
 Digital Signal Processing
</h3>
<ul>
 <li>
  <a href="https://github.com/vection/luafft">
   LuaFFT
  </a>
  - An easy to use Fast Fourier Transformation package in pure Lua.
 </li>
 <li>
  <a href="http://worp.zevv.nl/about.html">
   Worp
  </a>
  - Sound/music/DSP engine written for LuaJIT.
 </li>
</ul>
<h3>
 Hardware and Embedded Systems
</h3>
<ul>
 <li>
  <a href="http://www.eluaproject.net/">
   eLua
  </a>
  - Lua, extended with optimizations and specific features for efficient and portable embedded software development.
 </li>
</ul>
<h3>
 Math and Scientific Computing
</h3>
<ul>
 <li>
  <a href="http://scilua.org/">
   SciLua
  </a>
  - Numerical/scientific computing framework built on LuaJIT, with an interface to R.
 </li>
 <li>
  <a href="http://torch.ch/">
   Torch7
  </a>
  - Scientific computing framework with wide support for machine learning algorithms, used by Facebook, Google, and more.
 </li>
 <li>
  <a href="http://www.tecgraf.puc-rio.br/~lhf/ftp/lua/">
   lhf's Lua Tools
  </a>
  - Assorted libraries and tools, many math-related.
 </li>
</ul>
<h3>
 Parsing
</h3>
<ul>
 <li>
  JSON
  <ul>
   <li>
    <a href="https://github.com/mpx/lua-cjson/">
     lua-cjson
    </a>
    - Blazing fast JSON encoding/decoding implemented in C and exposed to Lua.
   </li>
   <li>
    <a href="https://github.com/harningt/luajson">
     luajson
    </a>
    - JSON encoder/decoder implemented in Lua on top of LPeg.
    <sup>
     &#9733 138, pushed 15 days ago
    </sup>
   </li>
   <li>
    <a href="http://dkolf.de/src/dkjson-lua.fsl/home">
     dkjson
    </a>
    - JSON encoder/decoder implemented in pure Lua.
   </li>
  </ul>
 </li>
 <li>
  XML
  <ul>
   <li>
    <a href="https://matthewwild.co.uk/projects/luaexpat/">
     LuaExpat
    </a>
    - SAX XML parser via binding to the Expat library.
   </li>
   <li>
    <a href="https://github.com/Phrogz/SLAXML">
     SLAXML
    </a>
    - Pure Lua SAX-like streaming XML parser.
    <sup>
     &#9733 71, pushed 14 days ago
    </sup>
   </li>
  </ul>
 </li>
 <li>
  <a href="https://github.com/gvvaughan/lyaml">
   lyaml
  </a>
  - YAML encoding/decoding via binding to LibYAML.
  <sup>
   &#9733 33, pushed 119 days ago
  </sup>
 </li>
 <li>
  <a href="http://www.inf.puc-rio.br/~roberto/lpeg/">
   LPeg
  </a>
  - A pattern-matching library for Lua, based on Parsing Expression Grammars.
 </li>
 <li>
  <a href="https://github.com/jgm/lunamark">
   lunamark
  </a>
  - Converts Markdown to other textual formats including HTML and LaTeX. Uses LPeg for fast parsing.
  <sup>
   &#9733 101, pushed 16 days ago
  </sup>
 </li>
</ul>
<h3>
 Humanize
</h3>
<ul>
 <li>
  <a href="https://github.com/kikito/i18n.lua">
   i18n.lua
  </a>
  - Internationalization library with locales, formatting, and pluralization.
  <sup>
   &#9733 47, pushed 30 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/kikito/inspect.lua">
   inspect.lua
  </a>
  - Human-readable representation of Lua tables.
  <sup>
   &#9733 290, pushed 23 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/pkulchenko/serpent">
   serpent
  </a>
  - Serializer and pretty printer.
  <sup>
   &#9733 120, pushed 98 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/gvx/Ser">
   Ser
  </a>
  - Dead simple serializer with good performance.
  <sup>
   &#9733 44, pushed 78 days ago
  </sup>
 </li>
</ul>
<h3>
 Compression
</h3>
<ul>
 <li>
  <a href="https://github.com/brimworks/lua-zlib">
   lua-zlib
  </a>
  - Simple streaming interface to zlib for gzip/gunzip.
  <sup>
   &#9733 83, pushed 45 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/brimworks/lua-zip">
   lua-zip
  </a>
  - Lua binding to libzip. Reads and writes zip files.
  <sup>
   &#9733 25, pushed 199 days ago
  </sup>
 </li>
</ul>
<h3>
 Cryptography
</h3>
<ul>
 <li>
  <a href="https://github.com/mkottman/luacrypto">
   LuaCrypto
  </a>
  - Lua bindings to OpenSSL.
  <sup>
   &#9733 48, pushed 183 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/somesocks/lua-lockbox">
   lua-lockbox
  </a>
  - A collection of cryptographic primitives written in pure Lua.
  <sup>
   &#9733 152, pushed 57 days ago
  </sup>
 </li>
</ul>
<h3>
 Network
</h3>
<ul>
 <li>
  <a href="https://github.com/diegonehab/luasocket">
   LuaSocket
  </a>
  - Networking extension which provides a socket API for TCP and UDP, and implements HTTP, FTP, and SMTP.
  <sup>
   &#9733 397, pushed 21 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/lipp/lua-websockets">
   lua-websockets
  </a>
  - WebSocket client and server modules. Webserver-agnostic, implemented in Lua on top of LuaSocket.
  <sup>
   &#9733 179, pushed 4 days ago
  </sup>
 </li>
</ul>
<h3>
 Data Stores
</h3>
<ul>
 <li>
  <a href="http://www.keplerproject.org/luasql/">
   LuaSQL
  </a>
  - Simple interface for connecting to ODBC, ADO, Oracle, MySQL, SQLite and PostgreSQL.
 </li>
 <li>
  <a href="https://github.com/nrk/redis-lua">
   redis-lua
  </a>
  - Pure Lua client library for Redis.
  <sup>
   &#9733 374, pushed 126 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/leafo/pgmoon">
   pgmoon
  </a>
  - Lua PostgreSQL driver for OpenResty and others.
  <sup>
   &#9733 74, pushed 8 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/openresty/lua-resty-mysql">
   lua-resty-mysql
  </a>
  - Lua MySQL driver for OpenResty.
  <sup>
   &#9733 218, pushed 162 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/openresty/lua-resty-redis">
   lua-resty-redis
  </a>
  - Lua Redis client driver for OpenResty.
  <sup>
   &#9733 563, pushed 42 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/jbochi/lua-resty-cassandra">
   lua-resty-cassandra
  </a>
  - Lua Cassandra client driver for OpenResty and others.
  <sup>
   &#9733 50, pushed 329 days ago
  </sup>
 </li>
</ul>
<h3>
 Testing
</h3>
<ul>
 <li>
  <a href="http://olivinelabs.com/busted/">
   busted
  </a>
  - BDD-style unit testing framework with great docs and Moonscript support.
 </li>
 <li>
  <a href="https://github.com/norman/telescope">
   telescope
  </a>
  - Flexible and highly customizable testing library.
  <sup>
   &#9733 110, pushed 6 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/Olivine-Labs/luassert">
   luassert
  </a>
  - Assertion library extending Lua's built-in assertions.
  <sup>
   &#9733 35, pushed 4 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/bjornbytes/lust">
   lust
  </a>
  - Minimal test framework.
  <sup>
   &#9733 5, pushed 107 days ago
  </sup>
 </li>
</ul>
<h3>
 Foreign Function Interfaces
</h3>
<ul>
 <li>
  <a href="http://luajit.org/ext_ffi.html">
   LuaJIT FFI
  </a>
  - LuaJIT's mechanism for calling external C functions and using C data structures from pure Lua code.
 </li>
 <li>
  <a href="https://github.com/jmckaskill/luaffi">
   luaffi
  </a>
  - Standalone FFI library, compatible with the LuaJIT FFI interface.
  <sup>
   &#9733 233, pushed 907 days ago
  </sup>
 </li>
</ul>
<h3>
 Analysis Tools and ASTs
</h3>
<ul>
 <li>
  <a href="https://github.com/sztupy/luadec51">
   luadec51
  </a>
  - Lua Decompiler for Lua version 5.1.
  <sup>
   &#9733 137, pushed 246 days ago
  </sup>
 </li>
 <li>
  <a href="http://keplerproject.github.io/luacov/">
   luacov
  </a>
  - Simple coverage analyzer, used by busted and telescope for checking test coverage.
 </li>
 <li>
  <a href="https://github.com/mpeterv/luacheck">
   luacheck
  </a>
  - Simple static analyzer which detects accidental globals and undefined or shadowed locals.
  <sup>
   &#9733 265, pushed 15 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/fab13n/metalua">
   Metalua
  </a>
  - Pure Lua parser and compiler, used for generating ASTs. A number of other tools make use of the Metalua parser in this way.
  <sup>
   &#9733 211, pushed 688 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/davidm/lua-inspect">
   LuaInspect
  </a>
  - Lua's most powerful code analysis and linting tool, built on Metalua. Used by ZeroBraneStudio, among others.
  <sup>
   &#9733 125, pushed 12 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/stravant/LuaMinify">
   LuaMinify
  </a>
  - Minifier which also brings its own static analysis tools, lexer, and parser.
  <sup>
   &#9733 95, pushed 309 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/andremm/typedlua">
   Typed Lua
  </a>
  - A typed superset of Lua that compiles to plain Lua.
  <sup>
   &#9733 247, pushed 4 days ago
  </sup>
 </li>
</ul>
<h3>
 Experimental, etc
</h3>
<ul>
 <li>
  <a href="https://github.com/TannerRogalsky/punchdrunk">
   punchdrunk.js
  </a>
  - Moonshine + LÖVE API reimplementation = run LÖVE games in the browser.
  <sup>
   &#9733 75, pushed 86 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/luvit/luvit">
   luvit
  </a>
  - Node.js's underlying architecture (libUV) with Lua on top instead of JavaScript.
  <sup>
   &#9733 2242, pushed 3 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/bjornbytes/graphql-lua">
   graphql-lua
  </a>
  - Lua implementation of
  <a href="http://graphql.org/">
   GraphQL
  </a>
  .
  <sup>
   &#9733 10, pushed 3 days ago
  </sup>
 </li>
</ul>
<h3>
 Scriptable by Lua
</h3>
<ul>
 <li>
  <a href="http://mason-larobina.github.io/luakit/">
   luakit
  </a>
  - Fast, small, webkit based browser framework extensible by Lua.
 </li>
 <li>
  <a href="http://www.hammerspoon.org">
   Hammerspoon
  </a>
  - A powerful, extensible OS X automation tool. A community-maintained fork of
  <a href="http://www.mjolnir.io/">
   Mjolnir
  </a>
  .
 </li>
 <li>
  <a href="https://github.com/skx/kpie">
   kpie
  </a>
  - A scripting utility to juggle windows.
  <sup>
   &#9733 19, pushed 164 days ago
  </sup>
 </li>
 <li>
  <a href="https://lumail.org/">
   lumail
  </a>
  - A console-based mail client, with extensive scripting capabilities.
 </li>
 <li>
  <a href="http://awesome.naquadah.org">
   AwesomeWM
  </a>
  - A highly configurable and extensible window manager for X, scripted and configured by Lua.
 </li>
 <li>
  <a href="http://foicica.com/textadept/">
   Textadept
  </a>
  - Extremely lightweight, customizable, cross-platform editor, written (mostly) in (and scripted by) Lua.
 </li>
 <li>
  <a href="https://github.com/koreader/koreader">
   KoReader
  </a>
  - An ebook reader application supports PDF, DJVU, EPUB, FB2 and much more, running on Kindle, Kobo, PocketBook and Android devices.
  <sup>
   &#9733 1824, pushed 2 days ago
  </sup>
 </li>
</ul>
<h3>
 Miscellaneous
</h3>
<ul>
 <li>
  <a href="http://moonscript.org/">
   MoonScript
  </a>
  - Moonscript is a dynamic scripting language that compiles to Lua. It reduces verbosity and provides a rich set of features like comprehensions and classes. Its author calls it 'CoffeeScript for Lua'.
 </li>
 <li>
  <a href="http://leafo.net/sitegen/">
   sitegen
  </a>
  - A static site generator which uses MoonScript and supports HTML and Markdown, page grouping, and plugins.
 </li>
</ul>
<h2>
 Resources
</h2>
<h3>
 References
</h3>
<ul>
 <li>
  <a href="http://www.lua.org/manual/5.3/">
   Reference Manual
  </a>
  - The official definition of the Lua language.
 </li>
 <li>
  <a href="http://lua-users.org/wiki/">
   lua-users wiki
  </a>
  - A large community-maintained collection of Lua information and resources, supplementing the official website.
 </li>
 <li>
  <a href="http://www.luafaq.org/">
   Lua Unofficial FAQ
  </a>
  - Answers all sorts of Lua-related questions, including many of the form 'How to
  <em>
   _
  </em>
  ?'.
 </li>
 <li>
  <a href="http://www.lua.org/lua-l.html">
   lua-l
  </a>
  - The official Lua mailing list, and one of the focal points of the Lua community.
 </li>
</ul>
<h3>
 Style Guides
</h3>
<ul>
 <li>
  <a href="http://lua-users.org/wiki/LuaStyleGuide">
   Lua-users style guide
  </a>
  - A general, high-level style guide; unopinionated, easily agreed on.
 </li>
 <li>
  <a href="https://github.com/Olivine-Labs/lua-style-guide">
   Olivine style guide
  </a>
  - A more opinionated and specific, and therefore more rigorous, guide.
  <sup>
   &#9733 144, pushed 113 days ago
  </sup>
 </li>
</ul>
<h3>
 Tutorials
</h3>
<ul>
 <li>
  <a href="http://www.coppeliarobotics.com/helpFiles/en/luaCrashCourse.htm">
   Lua Crash Course
  </a>
  - Short crash course readover, or reference for when you forget the basics.
 </li>
 <li>
  <a href="http://tylerneylon.com/a/learn-lua/">
   Learn Lua in 15 Minutes
  </a>
  - A well-commented example file which covers the basics.
 </li>
 <li>
  <a href="http://phrogz.net/lua/LearningLua_FromJS.html">
   Learning Lua from JS
  </a>
  - An overview of the similarities and differences between Lua and JS; a great start for JavaScript folks looking to pick up Lua.
 </li>
 <li>
  <a href="http://lua-users.org/wiki/LuaTutorial">
   lua-users tutorial
  </a>
  - In-depth collection of tutorials aimed at newcomers.
 </li>
 <li>
  <a href="https://github.com/kikito/lua_missions">
   Lua Missions
  </a>
  - A series of 'Missions' to work through which are designed to teach aspects of Lua along the way.
  <sup>
   &#9733 196, pushed 342 days ago
  </sup>
 </li>
 <li>
  <a href="http://leafo.net/posts/creating_an_image_server.html">
   Creating an Image Server
  </a>
  - Walks through setting up and using OpenResty to build a simple image processing server; a great starting point for playing with OpenResty.
 </li>
</ul>
<h3>
 Articles
</h3>
<ul>
 <li>
  <a href="http://www.debian-administration.org/articles/264">
   Embedding Lua in C
  </a>
  - An introductory walkthrough of embedding Lua in a C program. A bit dated, but still a great walkthrough.
 </li>
 <li>
  <a href="http://notebook.kulchenko.com/programming/lua-good-different-bad-and-ugly-parts">
   Lua: Good, bad, and ugly parts
  </a>
  - A thorough summary of the good, different, bad, and ugly aspects of Lua, including many subtle quirks, by the author of ZeroBraneStudio.
 </li>
 <li>
  <a href="http://www.thijsschreijer.nl/blog/?p=693">
   Lua states, libraries, coroutines and memory
  </a>
  - Diagrams and explains some more advanced concepts of the Lua VM, particularly when interfacing with C.
 </li>
</ul>
<h3>
 Talks & Slides
</h3>
<ul>
 <li>
  <a href="http://www.inf.puc-rio.br/~roberto/talks/index.html">
   Roberto's Talks
  </a>
  - History of talks given by Lua's chief architect, with slides for each.
 </li>
 <li>
  <a href="http://www.lua.org/wshop14.html#abstracts">
   Lua Workshop Talks
  </a>
  - High-quality talks are given at each ~annual Lua Workshop, and a history of them is online, slides included.
 </li>
</ul>
<h3>
 Books
</h3>
<ul>
 <li>
  <a href="http://www.lua.org/pil/">
   Programming in Lua
  </a>
  - The authoritative intro to all aspects of Lua programming, written by Lua's chief architect. Three editions released; first edition available online.
 </li>
 <li>
  <a href="http://www.lua.org/gems/">
   Programming Gems
  </a>
  - A collection of articles covering existing wisdom and practices on programming well in Lua, in a broad variety of use cases.
 </li>
 <li>
  <a href="https://en.wikibooks.org/wiki/Lua_Programming">
   Lua Programming
  </a>
  - A shorter overview of the language, up to date for Lua 5.2, and available online.
 </li>
</ul>
<h3>
 Other Lists
</h3>
<ul>
 <li>
  <a href="https://github.com/bungle/awesome-resty">
   awesome-resty
  </a>
  - A list like this one, but focused on OpenResty.
 </li>
 <li>
  <a href="https://github.com/JanWerder/awesome-love2d">
   awesome-love2d
  </a>
  - A list like this one, but focused on game dev and the LÖVE platform.
 </li>
 <li>
  <a href="https://github.com/forhappy/awesome-lua">
   awesome-lua
  </a>
  by @forhappy - Another list similar to this one. It goes into more depth in a few categories, but has less breadth.
  <sup>
   &#9733 122, pushed 624 days ago
  </sup>
 </li>
 <li>
  <a href="https://sites.google.com/site/marbux/home/where-lua-is-used">
   Where Lua is Used
  </a>
  - A comprehensive list of stand-alone programs written in or extensible using Lua.
 </li>
</ul>
<h2>
 Contribute
</h2>
<p>
 Contributions welcome and wanted! Read the
 <a href="contributing.md">
  contribution guidelines
 </a>
 first.
</p>
<h2>
 License
</h2>
<p>
 <a href="http://creativecommons.org/publicdomain/zero/1.0/">
  <img alt="CC0" src="http://i.creativecommons.org/p/zero/1.0/88x31.png"/>
 </a>
</p>
<p>
 To the extent possible under law, Lewis Ellis has waived all copyright and related or neighboring rights to this work.
</p>
