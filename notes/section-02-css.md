# CSS
CSS means Cascadian Style Sheets.  
You can make rules about the way you want things to be displayed on the page. 
   
Here's the configuration:  
  
If we want every h1 in the page to be red, so we have to do this:
h1 { the condition }  
  
We call the h1 the selector, and everything that will be inside the {} will be rules that your page will folow.  
  
Following our example,  
h1 { color: red; }  
color is called the **property**, because is something that will be applied.  
  
## Centering tables
I had some problem with centering table and found some usable content to help me, so I will put it here then I will can access another time. [Here's the link](https://www.granneman.com/webdev/coding/css/centertables).  
  
*Don't style by tags. Style by classes.*  
  
## Specificity
Classes are more spectific than tags. Tags are more generic. Think about sofas. When you say "sofas" it can ben any kind of sofa. But when you say "L sofa", it is more specific than just sofas.  
  
## Box-sizing
If you use the type of box-sizing called "content-box" (which is the default), you will have to calculate the size of the element not by the width or height but by the sum of margin and padding and the width and height, and it is not necessary, because you have the **box-sizing: border-box** and it already includes the margins and paddings inside the **entire size** (I mean the number of width and height). Remember that.  
For using border-box, all you have to do is:  
  
* {
    box-sizing: border-box;
}  
  
The selector * selects everything in the page, so you will be able to turn every box-sizing in the page to act as boder-box.