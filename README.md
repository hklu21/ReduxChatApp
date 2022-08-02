# ReduxChatApp
This is a chat app build with React/Redux, SocketIO and MongoDB. The navigation still is following with the [officail redux example](https://redux.js.org/tutorials/essentials/part-1-overview-concepts). The purpose for doing this project is to  adapt myself to redux framwork and to learn how to design state-heavied web application together with how to use SocketIO in real-time data interacted model.

[live demo](https://hklu-chat-rooms.herokuapp.com/home)(there is currently some bugs with the SocketIo on Heroku, but works fine on local host)

## Functionality

- Registration, Log in, Log out

- view / edit own profile, view others profile

- view chat rooms list and room's information (capacity, description, creator)

- create and join chat rooms

- instant messaging with other memebers in chat rooms

- check chat history / check online members

## ScreenShots

![plot](./screen_shots/shot_1.png)

![plot](./screen_shots/shot_2.png)

## How to run

### build the chat application

in this directory

``` SHELL
npm install

npm run build
```

### run the sever

 in this directory(have pymongo, flask, flask_socketio installed)

``` SHELL
python3 server.py
```

## Reference

[Redux Tutorials](https://redux.js.org/tutorials/essentials/part-1-overview-concepts)

[How to show and hide Password in ReactJS](https://www.geeksforgeeks.org/how-to-show-and-hide-password-in-reactjs/)

[post data from React to Flask](https://dev.to/dev_elie/sending-data-from-react-to-flask-apm)

[Issue: get [OPTIONS] method instead of [POST] in flask](https://stackoverflow.com/questions/68012921/i-get-options-method-instead-of-post-in-flask)

[manually invoke Link](https://stackoverflow.com/questions/29244731/react-router-how-to-manually-invoke-link)

[flask socketio CORS](https://stackoverflow.com/questions/29187933/flask-socketio-cors)

[How to execute useEffect hook only once](https://www.gosink.in/react-js-how-to-render-useeffect-only-once/)

[Moment.Js](https://momentjs.com/)

[time format to 24 hours in javascript](https://stackoverflow.com/questions/22347521/change-time-format-to-24-hours-in-javascript)

[How to specify max-height css property to Screen size](https://stackoverflow.com/questions/20488298/how-to-specify-max-height-css-property-to-screen-size)

[React’s useEffect cleanup function](https://blog.logrocket.com/understanding-react-useeffect-cleanup-function/)

[CSS change button style after click](https://stackoverflow.com/questions/42134731/css-change-button-style-after-click)

[Using WebSockets in React/Redux App](https://www.pluralsight.com/guides/using-web-sockets-in-your-reactredux-app)

[Check if two Dates are the same Day in JavaScript](https://bobbyhadz.com/blog/javascript-check-if-two-dates-are-same-day)'
