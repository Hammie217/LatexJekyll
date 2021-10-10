# Latex Jekyll
![Alt text](./LatexJekyll.png?raw=true "LatexJekyll website")
## Try it out
[Try it here](https://unruffled-ardinghelli-55d901.netlify.app)

## Getting started from scratch
1. Clone  
```git clone https://github.com/Hammie217/LatexJekyll.git```  
2. Change directory  
```cd LatexJekyll```  
3. Updating bundle to resolve dependecy errors
```bundle update```
> Before running `bundle update` command make sure your system meets the [Jekyll Installation Requirements](https://jekyllrb.com/docs/installation/).
4. Start Jekyll Server  
```jekyll serve```  
5. Connect to localhost  

## What is there?

### Title settings

 - title - Set the main page title
 - author -  Set the authors name on the title page. Removed if none defined.
 - date - Set the front page date. Removed if none defined.
 - abstract - Set the text for the abstract. Removed if none defined.


### Sections

 - Section - Sets font styling of section. Requires manual numbering. `<p  class="Section">1 &ensp; Introduction</p>`
 - Sub Section - Sets font styling of subsection. Requires manual numbering. `<p  class="SubSection">1.2 &ensp; Text Styles</p>`

### Body settings

 - BodyText - Sets paragraph settings for single column. `<p  class="BodyText">`
 - BodyText2Col  - Sets paragraph settings for double colum. `<p  class="BodyText2Col">`
 - BodyText3Col  - Sets paragraph settings for triple column. `<p  class="BodyText3Col">`
 - Justified - Justifies text to take 100% of the width. `<p  class="Justified">`

### Font sizes

 - tiny
 - scriptsize
 - footnotesize
 - small
 - normalsize
 - large
 - Large
 - LARGE
 - huge
 - HUGE

 ### Maths

 Maths is delivered using mathJax. An inline latex equation can be done with "\\( ... \\)" or on a new line using "\\[ ... \\]".