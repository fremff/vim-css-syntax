# Enhanced version of CSS syntax highlighting script file for vim, supports for CSS3 

##  Introduction
  
The script is based on the [original css syntax file](http://fleiner.com/vim/syntax/css.vim),
and support for CSS3 syntax highlighting.
This script include many of CSS3 Property,Attribute and Selector,
the prefix " -moz-,-webkit- ,-o-,-ms- " support,
and complete the At-rule groups, see the [link](https://developer.mozilla.org/en-US/docs/CSS/At-rule).
Also, it support the beautify CSS feature, you can use it to by the :CSSBeautify command.

##  For the CSSBeautify command :

/* Original */

style:

body{ width:680px ;
background-color:#FFF;
box-shadow: -1px 1px 3px #DDD;
padding: 10px
}
a:nth-of-type(2n) 
{
  background-color:#FFF!important
}
.class #id{border-radius:0px!important;}

/* After the command execution */

style:

body {
width: 680px ;
background-color: #FFF ;
box-shadow: -1px 1px 3px #DDD ;
padding: 10px ;
}
a:nth-of-type(2n) {
background-color: #FFF !important;
}
.class #id {
border-radius: 0px !important;
}

##  Screenshots:
![Example 1](http://i.imgur.com/HjD48SP.jpg)
![Example 2](http://i.imgur.com/MBzDyhm.jpg)
![Example 3](http://i.imgur.com/HR2nYl2.jpg)

