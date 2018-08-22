# daily-javascript-q9

While reviewing another developer's code, you come across the following: 

``` html
<div id="result" class="format-output"></div> 
<script> 
      /* 
      This is an example of using functions. A function is a collection 
      of statements with a name. You call the function by using its name. 
      If the function needs additional information to do its work, you 
      pass that information in the parenthesis after the function name. 
      var name = 'John Doe'; 
      */ 
      var info = getName(name); 
      document.getElementById("result").innerHTML = info; 

      function getName(fullname) { 
           if (!fullname) 
                return 'empty'; 
           var index = fullname.indexOf(' '); 
           if (index === -1) 
                return 'no index'; 
           var sub = fullname.substring(index + 1); 
           return sub; 
      } 
</script> 
```

What will be displayed when you review this code in the browser?

Choose the correct answer

1) John
2) no index
3) Doe
4) empty

4
