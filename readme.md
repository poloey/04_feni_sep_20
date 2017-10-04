# Class 04
### View [all class list](https://github.com/poloey/feni)

# You can write style in 3 ways
### Inline css
~~~html
<h1 style="color: green;">Heading</h1>
~~~

### internal css
~~~html
<h1>Heading</h1>
<style>
    h1 {
        color: green;
    }
</style>
~~~


### external css
~~~html
<link rel="stylesheet" href="style.css">
<h1>Heading</h1>
~~~

~~~css
h1 {
    color: green;
}
~~~


# color
### color name like red, green, blue
### hexadecimal   
hexa = 6 (a to f)    
decimal = 10  (0 to 9)
hexadecimal = 16 (0 to f)   
hightest value `f` is white    
lowest value is `0` is black   
white hexadecimal value = `#ffffff`  
black hexadecimal value = `#00000`  
when first 3 letter is as last 3 letter you can omit last 3 digit. like `#fff`

### rgb() 
rgb stands for red, green, blue   
rgb() its a function. which require 3 parameter. red, green, blue   
rgb a value is `0 to 255`   
so hightest value `255` is white   
so lowest value `0` is black  
white rgb value = `rgb(255, 255, 255)`   
black rgb value = `rgb(0, 0, 0)`   

### rgba()   
rgba stands for red, green, blue, alpha.
rga will be like state above rga. 4th parameter `a` stands for `alpha`. which define transparency. transparency maximum value is 1 and minimum value is 0.   
suppose I want black color with 50% transparency so value will be `rgba(0, 0, 0, 0,5)`    

# unit  
absolute unit: 
* px
* pt

relative unit:  
* em
* %
* rem

# font 
there are 3 types font   
* serif (with tail)
* sans-serif (without tail)
* monospace

#spacing
* margin   
margin will make spacing outside of container   
margin property:   
`margin` `margin-top` `margin-right` `margin-bottom` `margin-left`
	
* padding
padding will make spacing inside of container   
padding property:    
 `padding` `padding-top` `padding-right` `padding-bottom` `padding-left`   







