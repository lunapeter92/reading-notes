# Class 10 Notes
Notes taken from John Duckets Javascript/Jquery

## Error Handling and Debugging
  - Order of Execution: 
    - One of the basics of debugging is to known the order of execution for your script to know the steps it's supposed to take when run. 
  
  - Execution Context: 
    - Global Context: Code in the script, but in no function
    - Function Context: Code within a function
    - Eval Context: Text executed in code in an internal function called `eval()`.
    
  ### Error Objects: 
   - Error: Generic error, all other errors built on this. 
   - SyntaxError: Syntax has not been followed.
   - ReferenceError: Tried to reference a variable that is not declared/within scope
   - TypeError: unexpected data type that cannot be coerced. 
   - RangeError: Numbers not in acceptable range.
   - URIError: encodeURI(), decodeURI(), and similar methods used incorrectly.
   - EvalError: eval() used incorrectly. 

  ### Handling Exceptions: 
   - Try, Catch, Finally: 
     `if(response){
      try{
        //code that will try to do what you want. 
        }catch(e){
          //create error message
        }finally{
          //allows users to refresh page/data
        }
        
      }`
