Intro to JavaScript
=========

[Link]: https://classroom.udacity.com/courses/ud803

Lesson1.
---------

###History of JavaScript
> HTML and CSS are **markup languages**. Markup languages are used to describe and define elements within a document. JavaScript is a **programming language**. Programming languages are used to communicate instructions to a machine. Programming languages can be used to control the behavior of a machine and to express algorithms.



###### 에러 출력하기

`console.log`

```javascript
console.log("Hello friend!");
```

```javascript
for (var i = 0; i < 10; i++){
  console.log(i);
}
```





###### JavaScript로 CSS 수정하기

```javascript
document.getElementsByTagName("h1")[0].style.color = "#ff0000";
```

```css
document.body.addEventListener('click', function () {
     var myParent = document.getElementById("Banner"); 
     var myImage = document.createElement("img");
     myImage.src = 'https://thecatapi.com/api/images/get?format=src&type=gif';
     myParent.appendChild(myImage);
     myImage.style.marginLeft = "160px";
});
```

