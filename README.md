[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=450&size=35&pause=1000&color=BABBB3&center=true&width=435&lines=Hello+be+wellcome)](https://git.io/typing-svg)

---

```js
fetch("/archive.json")
  .then((response) => response.json())
  .then((data) => {
    console.log(data);
    var div = document.querySelector(".accordion-body");
    var p = document.createElement("div");

    var { name, age, currntly } = data.me;
    p.innerHTML = `
    <img src="${data.me.github_avatar}" class="avatar"/>
    <p class= "textHere">Name: ${name}</p>
    <p class= "textHere">Age: ${age}</p>
    <p class= "textHere">Currently: ${currntly}</p>
    <p class= "textHere">Techs: ${data.me.techs}</p>
    
    `;
    div.appendChild(p);
  });
```

```html
<div class="accordion-item">
  <div class="accordion-body">
    <div>
      <img
        src="https://avatars.githubusercontent.com/u/88904173?v=4"
        class="avatar"
      />
      <p class="textHere">Name: Rômulo</p>
      <p class="textHere">Age: 25 years</p>
      <p class="textHere">Currently: Learning node.js and Javascript</p>
      <p class="textHere">
        Techs: Bootstrap', 'HTML', 'CSS', 'Javascript', 'node.js
      </p>
    </div>
  </div>
</div>
```

```js
console.log("Give me a job");
```
