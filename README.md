# 👉 Working with JSON

<h1>  JSON - Introduction</h1>   
<p> JSON stands for JavaScript Object Notation

JSON is a text format for storing and transporting data

JSON is "self-describing" and easy to understand</p>

#  ✍️ JSON Syntax   
<p>
  JSON Syntax Rules<br>
JSON syntax is derived from JavaScript object notation syntax:


Data is separated by commas
Curly braces hold objects
Square brackets hold arrays    
<ul>
  <li>Data is in name/value pairs</li>
  <li>Curly braces hold objects</li>
  <li>Square brackets hold arrays  </li>
</ul>


</p>

```
'{"name":"rasel","age":23}'
```

# 👉 JSON.parse() 

```
const person='{"name":"rasel","age":23}' ;

const obj=JSON.parse(person );
console.log(obj);

```
#  👉 JSON.stringify() 

```
const man={
    
     name:"rasel mahmud",
     age:23,

     skills:["c++","javaScript","java"]
}

const text =JSON.stringify(man);
console.log(text);

```

#  👉 JSON Server  

```

async function fetchData(){
   const respose= await fetch("data.txt");
   const data= await respose.json();
    console.log(data.name);

}
fetchData();

``` 
 



