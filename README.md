# ReactJS-Admin
[![npm version](https://badge.fury.io/js/adminlte-reactjs.svg)](https://badge.fury.io/js/adminlte-reactjs)

ReactJS version of the original AdminLTE dashboard - https://github.com/Developer-Amit/myreact. This project consists of widgets, charts and other components written in ReactJS. Stylesheets are borrowed from the AdminLTE project. 

If you use React in your app, you might find some of these components useful!


##### Due to several work related commitments, the development rate is a little slow and I apologize for that. However, I'm looking for awesome folks :metal: who could contribute and help me maintain this project. If you have any queries that you may have on how to contribute, or you have just general questions about how to use the components in your app - feel free to shoot an email. I'll help you out! :smile_cat:


#### Instructions to run

- Fork or clone this repo. 
- Install nodejs and NPM
- Go to the project's root folder from your terminal and run `npm install`
- Run `node server.js`
- Going to [http://localhost:8000](http://localhost:8000) will render an empty dashboard skeleton in the client-side using ReactJS. Clicking on one of the dashboard options on the left pane displays the original dashboards from AdminLTE.
- Go to [http://localhost:8000/widgets.html](http://localhost:8000/widgets.html) to see available widgets in ReactJS.
- Use [React Developer Tools Chrome Extension](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en) to understand the components hierarchy and structure and to track down bugs.


#### For development

- React Hot Loader can be used to ease your development workflow. This can be done by installing dev dependencies from `package.json` file. If you haven't, then
run `npm install webpack-dev-server` and `npm install react-hot-loader`.
- Then in your HTML, change your javascript bundles' source paths to point to the webpack-dev-server proxy in your `script` tags. So if you have something
like this 

```html
<script src="/dist/js/vendors.js"></script>
<script src="/dist/js/app.bundle.js"></script>
```

change this to 

```html
<script src="http://localhost:8080/dist/js/vendors.js"></script>
<script src="http://localhost:8080/dist/js/app.bundle.js"></script>
```

For a detailed explanation on setting up a workflow using Webpack, check out my blog post - [Webpack for The Fast and The Furious](https://medium.com/@booleanhunter/webpack-for-the-fast-and-the-furious-bf8d3746adbd#.uzx2l0hy4) :oncoming_police_car:

This is still a work in progress and will get better over time. Will try and think of more essential features. 

#### Upcoming stuff

- Re-usable chart components
- Command line options to choose between client-side rendering and server-side rendering in ReactJS
- Including D3 / C3 charts 
