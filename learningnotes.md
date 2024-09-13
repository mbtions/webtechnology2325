CSS does not know where you are updating the property, it will also give ordered list-type to an unordered list.
Indexing => ordered (ex: roll no)
No Indexing => undordered

### Client-side rendering and server-side rendering
Why do we have thead tbody tags?
    while we create next app or create react app, if there is any change in the root element it will be rendered for the rest of its child elements and they are reloaded.
    => using browser 
    => using server => server-side rendering, you have to not render thead again and again therefore we can differentiate b/w head and body of table. and no more re-rendering of the same component(thead).

    vite => new react framework. rendering is fast.


