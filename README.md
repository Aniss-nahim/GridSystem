# Grid System
Grid system similar to materialize css responsive grid system using **flexBox**

## Documentation
Similar to m[aterialize](https://materializecss.com/) css ui framework we are using 12 columns fuild, this will help you layout your page in an **ordered easy way**.

### Container
`.container` class allows your <div> to act like a container.
`<div class="container"> ... </div>`

you can also use the `.full-container` which add some extrat width to your container.
`<div class="full-container"> ... </div>`

### Row
Rows are your flex-items reletive to your flex-container `.contaier` Or `.full-container`.
Rows are always displayed verticaly inside your container.
`<div class="container"> 
  <div class="row"> ... </div>
</div>`

### Col
`.col` class represents **one column unit** among the 12 columns you have in each row.
`<div class="container"> 
  <div class="row"> 
    <div class="col"> 12 column max in one single row </div>
  </div>
</div>`

### Creating responsive layouts
After we showed you how to layout elements using our grid system, now will show you how to design your **responsive layouts** so that they look clean and bretty.
  #### Screen Sizing table
 |      | Small devices (Mobile) < 769px | Medium devices (tablet, Desktop) < 993 | Large devices (Labtop, large desktop) >= 993|
 | ----------------|----| ---|----|
 | **Class prefix**| .s | .m | .l |
 | **container width** |  100%  |  90%  |  90%  |
 | **Number of Columns**|  12  |  12 | 12  |
 
 #### Example
 ` <div class="container">
      <div class="row">
        <div class="col s12"><p>s12</p></div>
        <div class="col s12 m4 l2"><p>s12 m4</p></div>
        <div class="col s12 m4 l8"><p>s12 m4</p></div>
        <div class="col s12 m4 l2"><p>s12 m4</p></div>
      </div>
      <div class="row">
        <div class="col s12 m6 l3"><p>s12 m6 l3</p></div>
        <div class="col s12 m6 l3"><p>s12 m6 l3</p></div>
        <div class="col s12 m6 l3"><p>s12 m6 l3</p></div>
        <div class="col s12 m6 l3"><p>s12 m6 l3</p></div>
      </div>
    </div>
   `
