
var xhr=new XMLHttpRequest;xhr.open("get","https://raw.githubusercontent.com/christofsteel/herosaver/master/herosaver.min.js",true);xhr.onreadystatechange=function(){if(xhr.readyState==4){var script=document.createElement("script");script.type="text/javascript";script.text=xhr.responseText;document.body.appendChild(script)}};xhr.send(null);
```

