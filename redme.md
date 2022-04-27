# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview]
  - The challenge: the challenge is to build out this interactive rating component and get it looking as close to the design as possible.
- My process: It took me 5 days to build this.
  - [Built with](#HTML5 #CSS3 #JAVASCRIPT.)
  - What I learned: I've learned how to use display block none in one <section> and then showing up after clicking on the submit button. And also I've learned more how to built a responsive page.
  - Continued development: I have to continue practice how to use the responsive page. 
  - Useful resources: https://www.w3schools.com/cssref/css3_pr_mediaquery.asp?msclkid=b19e7776c67511ecb597332cb3c06465
- [Author](Natali Marinho)
- Acknowledgments: javascript, css and html.]

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size (I tried)
- See hover states for all interactive elements on the page
- Select and submit a number rating
- See the "Thank you" card state after submitting a rating

### Screenshot
Tela 1: (./imagens/tela1.png)
Tela 2: (./imagens/tela2.png)
Tela 3: (./imagens/tela3.png)
Tela 4: (./imagens/tela4.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

```css
@media only screen and (max-width: 800px){
    body{
        padding-top: 120px;
    }
    
       section{
           margin: auto;
           width: 400px;
       }
    
       .text> p{
           font-size: 17px;
       }
       
       #greetings{
        margin: auto;
       }
    }
```
```js
function saida(){
    let entr = document.getElementById("entrada")
    entr.style.display = "none"
      let saida = document.getElementById("greetings")
    saida.style.display = "flex"
//nota.innerHTML = `You selected ${rating} out of 5`
}
```

### Continued development
I want to focus on mobile first semantic, flex box and js.


## Author

- Website - [Natali MArinho](https://www.your-site.com)
- Twitter - [@friidakhalo](https://www.twitter.com/friidakhalo)
