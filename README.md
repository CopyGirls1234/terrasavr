搜索关键代码：`window.document.location.href;`
删除关键代买所在的函数

```javascript
&&function(a){a=window.document.location.href;var b=a.indexOf("://yal.cc");0>b&&(b=a.indexOf("://yellowafterlife.itch.io"));0>b&&(b=a.indexOf("://v6p9d9t4.ssl.hwcdn.net"));return 0<=b&&8>
b}(this)
```


搜索关键代码：`window.document;`有两处

删除关键代买所在的函数

```javascript
&&function(a){var b=!0;try{var c=window.document;c=c[function(a){a="";for(var b=0,c;8>b;)c=b++,c=y.cca("ajdhqlhm",c),a+=va(c&-16|(c&15)+10*b+1&15);return a}(a)];var d=
c[function(a){a="";for(var b=0,c;4>b;)c=b++,c=y.cca("`zmn",c),a+=va(c&-16|(c&15)+16*b+8&15);return a}(a)];a="";c=0;for(var e;10>c;){var f=c++;e=y.cca('2)+wan"ik)',f);a+=va(e&-16|(e&15)+14*c+10&15)}var g=a;var h=d.indexOf(g);if(0>h){g="";e=0;for(var k;27>e;){var l=e++;k=y.cca(">-'{abli{onvaxlcjc&kpih(mm'",l);g+=va(k&-16|(k&15)+6*e+6&15)}h=d.indexOf(g)}if(0>h){k="";l=0;for(var q;43>l;){var t=l++;q=y.cca('=*"nbh`jaod\u007fd~wjulj`!bbjjghlsdv)fj`*l\u007ffclj"',t);k+=va(q&-16|(q&15)+8*l+5&15)}h=d.indexOf(k)}b=
0<=h&&8>h}catch(Qc){Qc instanceof z&&(Qc=Qc.val)}return b}(this)
```

将下面代码替换为`true`

下面这段代码其实是`三元比较符`组成，可以只保留中间值为`true`的代码

```javascript
(function(a){var b=!0;try{var c=window.document;c=c[function(a){a="";for(var b=0,c;8>b;)c=b++,c=y.cca("ajdhqlhm",c),a+=va(c&-16|(c&15)+10*b+1&15);return a}(a)];var d=c[function(a){a="";for(var b=0,c;4>b;)c=b++,c=y.cca("`zmn",c),a+=va(c&-16|(c&15)+16*b+8&15);return a}(a)];a="";c=0;for(var e;10>c;){var f=c++;e=y.cca('2)+wan"ik)',f);a+=va(e&-16|(e&15)+14*c+10&15)}var g=a;var h=d.indexOf(g);if(0>h){g="";e=0;for(var k;27>e;){var l=e++;k=y.cca(">-'{abli{onvaxlcjc&kpih(mm'",
l);g+=va(k&-16|(k&15)+6*e+6&15)}h=d.indexOf(g)}if(0>h){k="";l=0;for(var n;43>l;){var p=l++;n=y.cca('=*"nbh`jaod\u007fd~wjulj`!bbjjghlsdv)fj`*l\u007ffclj"',p);k+=va(n&-16|(n&15)+8*l+5&15)}h=d.indexOf(k)}b=0<=h&&8>h}catch(N){N instanceof z&&(N=N.val)}return b})(this)
```
