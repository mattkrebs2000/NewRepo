Instructions to re-create.

1. Go to Github create new repository (give it name you'd like your app to be called).
2. Copy link to new repository. 
3. In folder that you would like to house this new repository type: git clone {link}
4. (in command line type) cd {name of new repository that you initially gave it}
5. (inside folder type) create-react-app nameofapp
    note: on a different mac I had to do "sudo npm install -g create-react-app newapp" then in the folder "create-react-app newapp"
6. when its done take contents out of folder and place in the outer folder. 
7. (inside folder type) code .
8. (inside folder type) npm i -g expo-cli
    note: on a different mac I had to do "sudo npm install -g expo-cli" then in the folder "npm install expo-cli"
9. If yarn is not installed: "sudo npm install yarn" 
10. If react-native is not installed: "sudo npm install -g react-native"
11. (inside folder type) yarn add react-native-web@~0.11 react-dom
12. (inside folder type) expo start
13. if "React is not defined" go to app.js and paste "import React from 'react';" at the top of page. 
14. (inside folder type) w  
15. (inside folder type) i

If using windows you might have to replace the word "sudo" with "runas"