# Enhanced version of CSS syntax highlighting script file for vim, supports for CSS3 #

## Introduction
  
The script is based on the [original css syntax file](http://fleiner.com/vim/syntax/css.vim),
and support for CSS3 syntax highlighting.
Included many of CSS3 Property,Attribute and Selector,
and support for the prefix "-moz-,-webkit-,-o-,-ms-",too.  
About **At-rule groups** that in the script file, see the [link][1].  
Also, it support the ***Beautify CSS*** feature, you can use it to by the _:CSSBeautify_ command.

## Options

As a optional, "css_fast_sync" argument can be used for switch the syntax synchronization settings.
By default, to use `syn sync minlines=2000` as the setting of syntax synchronization.  
If you have a slow machine,then you can use the following option(to use `syn sync maxlines=200`):
```vim
let g:css_fast_sync = 1
```

## About the CSSBeautify command :

### *Original:*

```css
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

### *Applied the command:*

```css
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



[1]: https://developer.mozilla.org/en-US/docs/CSS/At-rule "At-rule"
