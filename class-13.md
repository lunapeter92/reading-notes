# Class 13 Notes
Notes taken from http://diveinto.html5doctor.com/storage.html

## Local Storage

  ### History of Storage
   - In the past native applications have reigned supreme when it came to storing data
   - Some ways that native applications were able to save data: 
    - Databases
    - XML files
    - Registry
   
   - One solution that web applications had was using cookies, but there were drawbacks: 
    - cookies have size limits
    - cookies could slow down application since they are included in every http request
    - cookies are unsafe in non encrypted applications

  ### HTML Storage
   - Web storage, local storage or HTML storage, is a way for HTML pages to store key/value pairs locally in the browser
   - Any data that is stored in local storage will persist even when there's a page refresh, or if you leave the site. 


  ### Code Snippets
    `let getItem = localStorage.getItem('data');`
    `let setItem = localStorage.setItem('data');`
    `let removeItem = localStorage.removeItem('data');`
