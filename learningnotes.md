CSS does not know where you are updating the property, it will also give ordered list-type to an unordered list.
Indexing => ordered (ex: roll no)
No Indexing => undordered

### Client-side rendering and server-side rendering
Why do we have thead tbody tags?
    while we create next app or create react app, if there is any change in the root element it will be rendered for the rest of its child elements and they are reloaded.
    => using browser 
    => using server => server-side rendering, you have to not render thead again and again therefore we can differentiate b/w head and body of table. and no more re-rendering of the same component(thead).

    vite => new react framework. rendering is fast.

action: 
method: method="get|post"
encryption type: enctype="multipart/form-data"


get => 
2 mb se upr ka data nhi bhej skta
apna data url mei merge krke bhejta hai (encrypt nhi hoti)

post => 
kitna bhi data bhej skta hai
alag se data, packet ki form mei jaata hai (bydefault encrypted hota hai)

url se differentiate mei get hee hota hai
fetch func post info bhejta hai.

light info that doesn't concern security we can use get there.

incase of refresh data can reappear for get requests whereas it doesnt comes back when used with post request. [also doesnt give suggestion] 

action => 
jis bhi lang ko data bhejna hai usko data bhejta hai (url usss lang ka hoga)


CSS

div.abc p {

}
div.abc > p {

}

#### using comma: {grouping}
div, section {

}

#### without using comma 
=> will group all descendants whether immediate child or their descendants as well

div.abc p {

}

#### using > selector {only immediate descendants selector}
div.abc > p {

}

#### using + selector {immediate sibling selector}
div.abc + p {

}

#### using ~ selector {For all sibling}
div.abc ~ p {

}

Q: why does the ~ is applied on siblings' descendants as well?
Q: Will the immediate sibling be applied on the element that is not just immediate as per the hierarchy? For ex: div.abc has immediate child as another div but + is applied on the p tag then will it be applied or not?


### Attributes Selectors
    element [attribute = "value"] {

    }
Ex: 
img [src="small.gif"] {
    border: 1px solid bisque;
}

Q: What is CSS and types of CSS
There are 3 types of CSS:
1. Inline: 
    In each and every tag, we have a style attribute, so we update this property.
2. Internal: 
    If we use style tag in the head or body
3. External: 
    When same css is written in an external file and link it with the html file using link tag.

Q: When to use which CSS?
=> NOTE: Always prefer external CSS, so that there will be a common styling for the page, 
i.e., For common interface. 
Also, if you are using common framework then also use it externally.
Internal: when you want to overwrite it for the elements, then use it internally.
Inline: When you want styling of a particular tag to be different then use inline

  order of CSS:
  - link
  - internal
  - inline

ID attribute in HTML has no syntactical meaning, it is just semantic for the understanding of the programmer.
