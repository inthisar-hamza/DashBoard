# DashBoard

StyleSheets and Javascript files are Created and Linked
Icons Resources are from -> https://ionicons.com/
Fonts are from -> https://fonts.google.com/

understanding:
>   :root is the pseudo class in CSS and It represent the root element.
>   In HTML, :root represent <html> or html selector

>   z-index represent the orders of element which is overlapping by its value

>   pseudo elements is the keyword added to the selector that let style specific part of element(s).
>   ::after/::before create pseudo element that is last/first child of selected element.

#example-element {
background-color: #e4f0f5;
color: #000;
padding: 1rem;
border-radius: .5rem;
font: 1em monospace;
width: 100%;
transition: margin-right 2s
}
#default-example:hover > #example-element {
background-color: #909;
color: #fff;
margin-right: 40%
}

<div id="output" class="output large hidden">
    <section id="default-example">
        <div id="example-element">Hover to see<br>the transition.</div>
    </section>
</div>
