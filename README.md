# 1.What are the types of Error in Javascript?
=> Generally 4 types the are
  1.syntax Error
  ->let java is fun=true;
  2.Reference Error
  ->console.log(value); output: ReferenceError: value is not defined
  3.Type Error
  ->let javaIsFun=true;
     console.log(javaIsFun.toUpperCase()); 
     output: TypeError: javaIsFun.toUpperCase is not a function
  4.Rage Error
->let myArray = [1, 2, 3];
   console.log(myArray[3]); // RangeError: Index out of range

# 2. Error Handile using throw and try and catch:code

# .sessionStorage vs localStorage
->Method are same but difference is if you close the browser sessionStorage clear
the data but not with localStorage:code