# HTML
We certainly always try to speed up the creation of code, two of the most commonly used methods<br>
we use are:<br>
* Adapt/Tweak/Re-use code<br>
* Emmet abbreviations that expands on full code/code snippets<br>

If the only option we have is to create code starting from the scratch, then Emmet is the tool to be used<br>
Emmet is and Add-on available for several text editors (Vscode, Sublime, Atom, etc.)<br>
It's already included on Vscode so everytime a valid abbreviation (built-in/custom) is recognized<br>
you'll see kind of a suggestion telling you that a Emmet abbreviation is available<br>
then you can press TAB to expand it, see images below:<br>
# Emmet abbreviation recognized<br>
<img src="/img/1.emmet-before.png" alt="Emmet abbreviation recognized"><br>
# Emmet abbreviation expanded<br>
<img src="/img/2.emmet-after.png" alt="Emmet abbreviation expanded"><br>
# Emmet cheat Sheet<br>
A complete list of abbreviations can be found in Emmet's official website available at:<br>
https://docs.emmet.io/cheat-sheet/<br>
<img src="/img/3.emmet-cheatsheet.png" alt="Emmet abbreviation expanded"><br>
# CSS Flexbox with Emmet<br>
The following example shows how to speed up CSS flexbox creation using Emmet<br>
<img src="/css-flexbox-emmet/css-flexbox-emmet.png" alt="Emmet abbreviation expanded"><br>
# Emmet abbreviation recognized<br>
Emmet custom abbreviation:<br>
`div#fl_bx_ctainer.flexbox-container>div#fl_bx_i$.flexbox-itemi$*3{$}`
CSS code:<br>
```CSS
.flexbox-container{
	background-color: rgb(242, 242, 232);
	display: flex;
	justify-content: space-around;
	align-items: flex-start;
}

.flexbox-item{
    width: 15%;
    background-color: rgba(85, 85, 88, 0.2);
    border: 5px solid #090909;
    font-size: 40px;
    color: blue;
    font-weight: bold;
    padding: 10px;
    margin: 5px;
}

.i1 {
    min-height: 50px;
}

.i2 {
    min-height: 100px;
}

.i3 {
    min-height: 250px;
}
```


