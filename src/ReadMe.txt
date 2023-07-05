So i tried to do this watching React tutorial for beginners on Programming with mosh channel .
start the project-->npm run dev


to run firebase login initially i have to do something in powershell 
like run powershell(or command prompt)as admin and then drop some security.



so it was a little difficult transpiling the typescript.finally found that instead of build folder it was going to the dist folder by default
i changed it by chaning the value of "public" to "build" in the firebase.json.and then {npm run build},and then {firebase deploy}
I also learned that {npm run preview} gives a production build locally and {npm run dev} gives a local build .
thanks to https://vitejs.dev/guide/static-deploy.html

maping function is also different in typesript