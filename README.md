# breakpointtester

Copied from http://breakpointtester.com/ in case the site goes down again, as it's a great tool.

Using http://rawgit.com/ to serve files.

## To use

Create a new bookmark with the following in the link field:

```
javascript:void((function()%7Bfunction e(e,t)%7Bvar n%3Ddocument.createElement(%27script%27)%3Bn.type%3D%27text/javascript%27%3Bif(n.readyState)%7Bn.onreadystatechange%3Dfunction()%7Bif(n.readyState%3D%3D%27loaded%27%7C%7Cn.readyState%3D%3D%27complete%27)%7Bn.onreadystatechange%3Dnull%3Bt()%7D%7D%7Delse%7Bn.onload%3Dfunction()%7Bt()%7D%7Dn.src%3De%3Bdocument.getElementsByTagName(%27head%27)%5B0%5D.appendChild(n)%7De(%27https://cdn.rawgit.com/kiwimind/breakpointtester/master/assets/js/breakpoint.js%27,function()%7Bvar e%3Ddocument%3Be.write(%27<!DOCTYPE html>%27%2B%27<html>%27%2B%27<head>%27%2B%27<meta charset%3D"UTF-8">%27%2B%27<title>Breakpoint Test - %27%2Be.title%2B%27</title>%27%2B%27<link rel%3D"stylesheet" href%3D"https://cdn.rawgit.com/kiwimind/breakpointtester/master/assets/css/bookmark.css">%27%2B%27<script src%3D"https://cdn.rawgit.com/kiwimind/breakpointtester/master/assets/js/bookmark.js"></script>%27%2B%27</head>%27%2B%27<body data-url%3D"%27%2Be.URL%2B%27">%27%2B%27<header id%3D"topHeader" class%3D"clearfix">%27%2B%27<a href%3D"%23"></a>%27%2B%27</section>%27%2B%27<section id%3D"bpCount">%27%2B%27<div id%3D"count">00</div>%27%2B%27<div id%3D"countText"><span>BREAKPOINTS FOUND</span></div>%27%2B%27</section>%27%2BmqUniqueBP%2B%27</header>%27%2B%27<section id%3D"qcWWW">%27%2B%27<ul id%3D"qcWW"></ul>%27%2B%27</section>%27%2B%27</body>%27%2B%27</html>%27)%3B%7D)%3B%7D)())%3B
```
