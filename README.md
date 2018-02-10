# nodejs-helloworld

1.  **Install Node.js for your platform (MacOS, Windows or Linux)**

2.  [**Open a command prompt and
    type:**](https://www.git-tower.com/blog/command-line-cheat-sheet/)
    
        mkdir myapp && cd myapp

3.  ``` 
    Initialize our project and link it to npm
    ```
    
        yarn init

4.  **** Install Express in the *myapp* directory  
    ****
    
        yarn add express

5.  ****Start your text editor of choice and create a file
    named *index.js*.   
    ****
    
        var express = require('express');
        var app = express();
    
        app.get('/', function (req, res) {
          res.send('Hello World!');
        });
    
        app.listen(3000, function () {
          console.log('Example app listening on port 3000!');
        });

6.  ****Run the app  
    ****
    
        node index.js
