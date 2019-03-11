# Introduction 

JavaScript was initially created to “make web pages alive”. The programs in this language are called scripts. They can be written right in a web page’s HTML and executed automatically as the page loads. Scripts are provided and executed as plain text. They don’t need special preparation or compilation to run.

Today, JavaScript can execute not only in the browser, but also on the server, or actually on any device that has a special program called the JavaScript engine. The browser has an embedded engine sometimes called a “JavaScript virtual machine”.Different engines have different “codenames”. For example:

* V8 – in Chrome and Opera.

* SpiderMonkey – in Firefox.

* There are other codenames like “Trident” and “Chakra” for different versions of IE, “ChakraCore” for Microsoft Edge, “Nitro” and “SquirrelFish” for Safari, etc.

> How do engines work?
> Engines are complicated. But the basics are easy.

> > The engine (embedded if it’s a browser) reads (“parses”) the script.
> > Then it converts (“compiles”) the script to the machine language.
> > And then the machine code runs, pretty fast.
> > The engine applies optimizations at each step of the process. It even watches the compiled script as it runs, analyzes the data that > > > flows through it, and applies optimizations to the machine code based on that knowledge. When it’s done, scripts run quite fast.
