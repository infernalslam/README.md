# README.md
ลองเล่น wordpress + กับการเทสhttp://www.nightmarejs.org/
การทดลองเขียน nightmare เอาไว้เทสการทำงานของweb 

    wordpress : https://programmer9468.wordpress.com/
    ต่อไปจะลองทำ speechWebapi



```
api.ai :website()
```
npm : https://www.npmjs.com/package/apiai

```javascript
var apiai = require('apiai')
 
var app = apiai("<your client acces token>", "<your client subscribtion key>")
 
var request = app.textRequest('<Your text query>')
 
request.on('response', function(response) {
    console.log(response)
})
 
request.on('error', function(error) {
    console.log(error)
})
 
request.end()
```
