![LumenJS Reactive JavaScript Framework](https://www.lumenjs.com/images/lumenjs.svg)

# LumenJS Reactive JavaScript Framework

LumenJS is a tiny robust reactive javascript framework for building scalable and high-performant web applications and web user interfaces, be it simple or complex, with standard HTML, CSS and JavaScript.
<a href="https://www.lumenjs.com/" target="_blank">LumenJS Documentation</a>



LumenJS comes along with MobiusCSS library which is a utility-first CSS framework packed with grid and table sectioning systems and classes like g, mt20, pv100, c and sq that can be composed to build any design, directly in your markup.
<a href="https://www.lumenjs.com/mobius" target="_blank">MobiusCSS Documentation</a>

&nbsp;

## Installation
Using npm:
```
npm install -g @lmjs/cli
```

&nbsp;

## USAGE
Create A New Project
```
lm create My Project Name
```
You can use lu, lm, or lumen as a command.

&nbsp;

Run The Project
```
lm serve
```

&nbsp;

Create A View
```
lm create -v myview
```

&nbsp;

Create A Sub View
```
lm create -s mysubview
```

&nbsp;

Create A Template
```
lm create -c mytemplate
```

&nbsp;

Purge Offline Cache Files (For Offline Usage)
```
lm purge
```

&nbsp;

Build A Dist For Production Version without NodeJs Server
```
lm build --serverless
```

&nbsp;

Build A Dist For Production Version without NodeJs Server & Deploy It Directly
```
lm build --serverless --deploy
```

&nbsp;

Build A Dist For Production Version + NodeJs Server
```
lm build
```

&nbsp;

Build A Dist For Production Version + NodeJs Server & Deploy It Directly
```
lm build --deploy
```
