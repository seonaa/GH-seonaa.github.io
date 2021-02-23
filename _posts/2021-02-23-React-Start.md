---
layout: post
author: 개발하는도비
---

### 2021-02-23 React

## package.json
keep `start`, `build` the other file delete after npm start.

## src/
- index.js :
line 3, 5, 7 to 10 delete

- Delete src/logo.svg
- Delete src/index.css
- Delete src/app.test.js
- Delete src/ app.css

## why react is fast?
- cause react is virtual and not exist.

## App.js
- in App.js use index.js Rendering, and index.html's id tag

## src/index.js
ReactDOM.render(<React.StrictMode>`<App/>`</React.StrictMode>, document.getElementById('potato'));
- `<App/>` is component.
- react working always with component.
- you make component and from component show data

## What's the Component?
- Component is the function that returns HTML
- It have function, application and returns HTML
- This calls `JSX` from javascript, HTML like `<APP />`
- That's only thing in Custom from React

## Use Component from JSX
ReactDOM.render(\<App/> \<Beach/> , document.getElementById('potato'));

If you follow this line, you'll see this error:
![component error](/assets/component_error.png)
 
<br><br> 
As you can see, A Component next to B Component is not working,<br>
you should App.js import B Component and use Component tag.
![use component](/assets/bComponents.png)

<br>

