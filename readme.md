# Enhanced version of CSS syntax highlighting script file for vim, supports for CSS3 

##  Introduction
  
The script is based on the [original css syntax file](http://fleiner.com/vim/syntax/css.vim),
and support for CSS3 syntax highlighting.
This script include many of CSS3 Property,Attribute and Selector,
and the prefix " -moz-,-webkit- ,-o-,-ms- " support,
and complete the At-rule groups, see the [link](https://developer.mozilla.org/en-US/docs/CSS/At-rule).
Also, it support the beautify CSS feature, you can use it to by the :CSSBeautify command.

## Options

As a optional, "css_default_sync" argument can be used for switch the syntax synchronization settings.
By default, to use "syn sync minlines=2000" as setting of synchronization. If you have a slow machine,
so, you can use the following option(to use "syn sync maxlines=200"):
```
let g:css_default_sync == 1
```

##  For the CSSBeautify command :

/* Original */

Style:

```
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
```

/* After the command execution */

Style:

```
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
```

##  Screenshots:
![Example 1](http://i.imgur.com/HjD48SP.jpg)
![Example 2](http://i.imgur.com/MBzDyhm.jpg)
![Example 3](http://i.imgur.com/HR2nYl2.jpg)


