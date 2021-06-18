# REACT STUDY NOTES

## check node version, npm version
node -v

npm -v


##  Start a new react application
npx creat-react-app myappname //no Capitalized name

##  Tools
* Extension  - *React Developer Tools* for Chrome, Firefox or Edge
* VS code
* React-Code Sandbox(Online IDE) https://codesandbox.io/s/react-new?file=/src/App.js
* https://babeljs.io/  click  *try it out*
* www.netlify.com   deploy your app through **netlify**
* https://www.uidesigndaily.com/
* React Icons:  npm install react-icons --save

## Useful online course
  * React.js Essential Training  (LinkedIn learning, by Eve Porcello)
  * https://reactrouter.com
  * FreeCodeCamp React Projects - Complete Course  https://www.youtube.com/watch?v=a_7Z7C_JCyo
  
## Delpoy App on netlify
npm run build
npm install -g serve
serve -s build

got to netlify website
drag the folder of build to netlify

## 
* Destructuring arrays and objects
* import photos
* * import photos from public folder (root) which index.html file located
* * import as a component as same folder as component

## Questions 
* Do you need both package-lock.json and package.json? No.
* Do you need the package.json? Yes.
* Can you have a project with only the package-lock.json? No.
* The package.json is used for more than dependencies - like defining project properties, description, author & license information, scripts, etc. The package-lock.json is solely used to lock dependencies to a specific version number.
* package-lock.json: records the exact version of each installed package which allows you to re-install them. Future installs will be able to build an identical dependency tree.
* package.json: records the minimum version you app needs. If you update the versions of a particular package, the change is not going to be reflected here.
<br/>
* manifest.json ?
 It's a Web App Manifest that describes your application and it's used by e.g. mobile phones if a shortcut is added to the homescreen.




 
