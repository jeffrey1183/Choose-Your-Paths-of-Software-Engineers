# JavaScript Demo

# Demo 1
Open [the following site](https://daringfireball.net/projects/markdown/) in a new tab and in that tab also open up developer tools. Then paste the following code:

```Javascript
document.getElementsByTagName("h1")[0].style.color = "#ff0000";
```

What happened when you ran that line of code in the JavaScript console?

**Yes! That line of code changes the text in the first `<h1>` tag to red!**

----

# Demo 2

Styling elements on the page is great, but you could also do that by just modifying the CSS. What makes JavaScript so special in this case? 

Refresh the page, then paste this line of code in the JavaScript console.

```Javascript
document.body.addEventListener('click', function () {
var myParent = document.getElementById("Banner"); 
     var myImage = document.createElement("img");
     myImage.src = 'https://thecatapi.com/api/images/get?format=src&type=gif';
     myParent.appendChild(myImage);
     myImage.style.marginLeft = "160px";
     
});
```

If you’re confused because nothing happened. Don’t worry. Click somewhere on the page.

**You will [see an image on the page](https://www.youtube.com/watch?v=gl-1VJ8Pcro).**


