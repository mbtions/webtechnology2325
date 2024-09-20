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

#### using comma:
div, section {

}

#### without using comma


#### using > selector {descendants selector}


#### using + selector {immediate sibling selector}
