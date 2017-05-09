# Data Playground 

Data Playground is a Full Stack Chat Room Server, that runs on Django for the Backend and REACT for the Frontend. 

Once the application is set up and running you can register and login by visiting `localhost:8000/users` on your browser.
(https://cloud.githubusercontent.com/assets/24658548/25831445/241d9cdc-3432-11e7-86d9-02e272642473.png)

Then by either clicking Chatroom on the navigation bar or visiting `localhost:8000/chatroom` you can try using the chat application.


The application runs on multiple frameworks and libraries so be prepared to install the following.

Python Libraries and Frame Works:
* django
* djangorestframework
* django-webpack-loader
* channels

Setting up Javascript and Webpack:
1) Please have node.js installed.
2) Run `npm install` in your root directory. This will install all javascript dependencies
3) Next run `webpack --config webpack.config.js`. This will create all the javascript bundles needed to run the App

Afterwords just run `python manage.py runserver` in the root directory
