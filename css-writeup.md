---

---

# Process Writeup

## Name: Zixuan Yu
## Course: SEP10
## Period: 2
## Concept: CSS

### Context
In the SEP 10 course, we are learning about basics of css after learning basics of HTML. HTML is the content of the website and CSS is where you customize how the website looks like partially. The website that helps me learn CSS is [FreeCodeCamp](freecodecamp.org), [replit](replit.com). In this writeup I will show you my process of learning CSS.
### Process of learning CSS
I will also have tips at the top of my table of properties like the format of using CSS, Class declaration, syntax for class, id, etc.
> ```Selector { property:value; }```

Freecodecamp is an online course website that teaches me about coding, I use FreeCodeCamp to learn CSS, each lesson I read the instruction and explanation carefully and taking notes on my table of CSS properties of each properties and it's function into my SEP notes. Like, the name of the properties, what it will do, what can it also do, and an example of the that showing how to use the properties. For example:

Input:
```css
h2 {
    font-weight: bold;
}
.italic {
    font-style: italic
}
```
```html
<h2>Hello World!</h2>
<p class=”italic”>Hello World!</p>
```
Output:

**Hello World!**

_Hello World!_

### Challenge 1

When I am playing CSS Diner, learning what each selector do, it is very hard for me to understand how to use it. For example, in level 16, I am suppose to select the apples and pickle on the plate. The description is teaching me how to use only child selector. Base of the example, I thought that to select the apples and pickle on the plate. I need to do ```plate:only-child``` but it did not work. It took me a very long time trying to figure out why the code won't work. Then I go back to previous levels I have done, I realize that level 14 is select the apple on the plate, then I realized that instead of doing ```plate:only-child``` you are suppose to add a ```>``` so it is selecting the elements on the plate. And I tried ```plate>:only-child``` and it worked.
```html
<div class="table">
    <plate>
        <apple />
    </plate>
    <plate>
        <pickle />
    </plate>
    <bento>
        <pickle />
    </bento>
    <plate>
        <orange class="small" />
        <orange />
    </plate>
    <pickle class="small" />
</div>
```
### Challenge 2

When we learning about hexcode in FreeCodeCamp, the course did teach us how to read hexcode but did not teaches us how to figure out hexadecimal, only teaches us the meaning of the number and alphabets in the hexcode. So since there is 15 numbers total, I thought it might be by multiply the first number by the second number, but total number is 225 and the maximum number is suppose to be 255 (Same as rgb system). So I google "how to read hexcode" and I found this website "[How To Read Hex Color Codes](https://www.pluralsight.com/blog/tutorials/understanding-hexadecimal-colors-simple)" and the equation on finding hexadecimal color is ```16a+b```, where the first number is ```a``` and the second number is ```b``` (summarize the equation). I did a little calculation to see if the equation is true, 15 x 16 = 240 and then add 15 = 255. That is the maximum number in rgb system so this is true.

### Takeaway
* This way of taking notes helps me memorize on what each properties do and how to use it.
* If I forget it, it is very easy for me to look it into my notes and knowing how to use the properties.
* Google is a useful tool when you don't know almost anything.
* Actually understand a lesson first then move on to the next lesson, or else you wouldn't understand what it is talking about.