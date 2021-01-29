
### Installation Steps

change the directory to MY-REACT


```bash
$ npm install
```

### To run dev server

App will start on localhost 3000

```bash
$ yarn start
```

### For the production build to 


```bash
$ yarn build
```

### How it is Built(To build PWA)

* Initial Project structure needs to be created with the command


```bash
$ npx create-react-app my-app --template cra-template-pwa
```

* The above command will create the structure of pwa
* It gives service-worker.js in the src folder(which has the capability of adapting to screen sizes)
* It also has manifest.json file under public folder, the start url and scope url needs to be changed to "/"
* In the index.js file under src folder, serviceWorkerRegistration.register() should be there instead of unregister()