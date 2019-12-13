## Tags
Tags are components thats make possible to select which part of the document you are and use many funcionalities.  
As example we have the **head**, **body**, the title tags (**h1** and the following tags), and a lot of 
another tags that gives us the power to structure our code.  
### Opening, closing tags and content
We have tags with some content inside and for this we need the opening tags and the closing tags.  
As example: < h1 >Hi</ h1 >. *Note: The spaces between the greater and lesser than are just for formatting, if it do not happens the archive will read it as a title*. We call content what will be in the users screen.  
### Self closing tags (or void tags)
But we also have tags that does not have (or need) any kind of content for existing (that's why it is also called void tags) and for this we call self closing tags.  
As example: < meta charset="utf-8">. This tag does not needs any content for existing, it's just signaling to the browser which kind of charset we will use in our website.

  
*Disclaimer: things can look different across the browsers, but you can make it look the same through CSS*
### Image tag
You have to use it when the image is a part of the content you want to show to the user, so you put in your HTML code. You can only use CSS when the image is purely decorative (as example: the background - if you will have one). *Use the alt attribute for screen readers and for SEO recongnizes the image and the content on your website*
### Input and Textarea
The only difference behind an input and a textarea is that the textarea accepts more text and the user can resize the space.
The textare also accept an initial value without an attribute (because it is not a self closing tag).
## Attributes
Attributes are related to tags. It gives more information about the "behavior" of the tag - it gives more power to us, developers. As example, we have the different attributes for the "input" tag.
## Elements
Elements are instances of tags. As example, we have seven input tags (with different attributes) by the line 62, so we have seven elements of the input tag.
## Classes
Think in a class like a label. You're labeling things so you can access then more easy.  
*Classes in general are more generic than IDs*  
*One element can have multiple classes but can't have multiple IDs*