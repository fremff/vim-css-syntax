# Enhanced version of CSS syntax highlighting script file for vim, supports for CSS3 

##  Introduction
  
The script is based on the official css syntax file, you can find it [in here](http://fleiner.com/vim/syntax/css.vim)
CSS3 syntax highlighting support. Include many of CSS3 Property,Attribute,Selector,
support for the prefix " -moz-,-webkit- ,-o-,-ms- ", and complete the At-rule groups,
see : https://developer.mozilla.org/en-US/docs/CSS/At-rule
Added beautify CSS file function,  use the :CSSBeautify command.


##  For the CSSBeautify command :

/* Original */

style

*{ width:680px ;
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

style

* {
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

