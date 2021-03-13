# FormValueGetter
A Javascript Plugin For Get Value Of All Html Forms Simply , Compatible with React and without JQuery


# example 
```
   let formdata = new FormValueGetter(document.getElementById('form_id'))
   console.log(formdata.obj) //get value as object 
   console.log(formdata.json) //get value as json 
   console.log(formdata.str) //get value as  string
```
You should passed the form as a object

# example in React
```
   ... class 

   //a class method 

   FormSubmitHandler(e){
       e.perventDeafault();
       let formdata = new FormValueGetter(e.target);
       console.log(formdata.obj) //get value as object 
       console.log(formdata.json) //get value as json 
       console.log(formdata.str) //get value as  string
   }
    
  
```
You should passed the form as a object
