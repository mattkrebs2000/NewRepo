Instructions to re-create.

1. Go to Github create new repository (give it name you'd like your app to be called).
2. Copy link to new repository. 
3. In folder that you would like to house this new repository type: git clone {link}
4. cd {name of new repository that you initially gave it}
5. (inside folder type) create-react-app nameofapp
    note: on mac I had to do "sudo npm install -g create-react-app newapp"
6. when its done take contents out of folder and place in the outer folder. 
7. (inside folder type) code .
8. (inside folder type) npm i -g expo-cli
9. (inside folder type) yarn add react-native-web@~0.11 react-dom
10. (inside folder type) expo start
11. if "can't find react" go to app.js and paste "import React from 'react';" at the top of page. 
12. (inside folder type) w  
13. (inside folder type) i