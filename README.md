# 100 Days Of Code - Log
### Day 8: 27/11/2018

**Todays progress**

* Began looking into OAuth2 authentication
* Set up a .NET Core simple api project

**Thoughts**

* Non.

**Thoughts**

### Day 7: 26/11/2018

**Todays progress**

* Solved yesterdays problem by implementing the experimental/proposal version of babels class properties
```
plugins: [
            '@babel/plugin-proposal-class-properties',
            ["@babel/plugin-transform-react-jsx", { "pragma":"h" }]
			]
```
* Started to look into states of components and how props can be passed backwards and forwards
* Updated the login button to render a loader when the state is changed. This uses `keyframes` in css.

**Thoughts**

* Need to do more research into keyframes to understand their limitations and usages.
* css can be powerful by itself and there is no need to rely on js to animate DOM elements.
* States are confusing at first. Need to sit down and full understand the lifecycle of preact.
* Quite glad I chose preact - with not much coverage its good to investigate and issue rather than have the answer handed to you.

### Day 6: 25/11/2018

**Todays Progress**
* Played around with css transformations and transitions. 
* Improved the login page ui by implementing feather icons.
* Tried to implement and onclick function in preact using the latest syntax. Had a few issues which I need to look into and read around to solve.
* Did a small amount of reading about SPA authentication.

**Thoughts**
* Having issues with preact when trying to call a function with the `onclick` method. Not sure why as the examples and reading material I followed the examples work fine with the syntax. It maybe that I missed something...

```
[WDS] Errors while compiling. Reload prevented. index.js:161:4
./src/Pages/Login.js
Module build failed: SyntaxError: C:\Users\John\Desktop\zero-to-preact-master\src\Pages\Login.js: Support for the experimental syntax 'classProperties' isn't currently enabled (9:11):

   7 | 
   8 | export default class Login extends Component {
>  9 |     state = { loading: false };
     |           ^
  10 | 
  11 |     login = (e) => {
  12 |         let checked = !this.state.loading;

Add @babel/plugin-proposal-class-properties (https://git.io/vb4SL) to the 'plugins' section of your Babel config to enable transformation.
    at _class.raise (C:\Users\John\Desktop\zero-to-preact-master\node_modules\@babel\parser\lib\index.js:4028:15)
    at _class.expectPlugin (C:\Users\John\Desktop\zero-to-preact-master\node_modules\@babel\parser\lib\index.js:5348:18)
    at _class.parseClassProperty (C:\Users\John\Desktop\zero-to-preact-master\node_modules\@babel\parser\lib\index.js:8235:12)
    at _class.pushClassProperty (C:\Users\John\Desktop\zero-to-preact-master\node_modules\@babel\parser\lib\index.js:8199:30)
    at _class.parseClassMemberWithIsStatic (C:\Users\John\Desktop\zero-to-preact-master\node_modules\@babel\parser\lib\index.js:8138:14)
    at _class.parseClassMember (C:\Users\John\Desktop\zero-to-preact-master\node_modules\@babel\parser\lib\index.js:8075:10)
    at _class.parseClassBody (C:\Users\John\Desktop\zero-to-preact-master\node_modules\@babel\parser\lib\index.js:8030:12)
    at _class.parseClass (C:\Users\John\Desktop\zero-to-preact-master\node_modules\@babel\parser\lib\index.js:7980:10)
    at _class.parseExportDefaultExpression (C:\Users\John\Desktop\zero-to-preact-master\node_modules\@babel\parser\lib\index.js:8347:19)
    at _class.parseExport (C:\Users\John\Desktop\zero-to-preact-master\node_modules\@babel\parser\lib\index.js:8298:31)
 @ ./src/components/app.js 23:0-37
 @ ./src/index.js
 @ multi (webpack)-dev-server/client?http://localhost:8080 webpack/hot/dev-server ./src
```

Hmm.


### Day 5: 24/11/2018

**Todays Progress**

* Worked on login page using css

**Thoughts**

* CSS looks good when you do a number of small features.
* A lot of new properties have been added since I properly last looked at css.
* Starting to appreciate small tweaks make a big difference.

### Day 4: 23/11/2018

**Todays Progress**

* Read more about WebPack and the implementation of rules
* Began building using SASS over just using and exisiting css framework.

**Thoughts**

* SASS is easier than I originally thought.
* WebPack is a beautiful powerful tool that I should have used earlier.
* Need to think more in depth about folder structure of files.

### Day 3: 22/11/2018

**Today's Progress**

* Lots of reading - mainly WebPack and more NoSql Distilled.
*   Understand the differences between `default exports` and `named exports`
* Restarted another test project from scratch implementing webpack
* Decided to move forward with preact without the dependencies of react - this could be interesting. Pure Preact FTW!

**Thoughts:**

* Slow down and learn thing slightly more in depth.
* Also make sure to use up to date information. The days of `babel-loader-es2015` are long gone! Google sort your indexing!

### Day 2: 21/11/2018

**Today's Progress**:

* Began reading NoSQL Distilled by Pramod J. Sadalage to gain insight if NoSQL is the correct approach for my project
* Implemented preact-router on my test application.

**Thoughts:**

* need to understand the difference between `import {entity} from ..` and `import entity from ..`
* Routing on single page applications through components seems the be a good idea for small based web API solutions.
* The power of NoSQL clusters seems to be the future with the vast amounts of data that is being collected.

### Day 1: 20/11/2018

**Today's Progress**: 

* Set-up NPM on laptop, installed preact and [(P)react Fluid](https://ajainvivek.github.io/preact-fluid/ "Preact Fluid")
* Created a simple application and and called in a simple component element.

**Thoughts:** 

* Props are incredibly overpowered. 
* Need to get the way vue.js works out of my head.
* Need to look into routing.
* Need to look into webpack.

**Link to work:** I'll link when I have something substantial. 

