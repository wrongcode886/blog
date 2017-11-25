Javascript:<br>
<br>
网页可见区域宽： document.body.clientWidth<br>
网页可见区域高： document.body.clientHeight<br>
网页可见区域宽： document.body.offsetWidth (包括边线的宽)<br>
网页可见区域高： document.body.offsetHeight (包括边线的高)<br>
网页正文全文宽： document.body.scrollWidth<br>
网页正文全文高： document.body.scrollHeight<br>
网页被卷去的高： document.body.scrollTop<br>
网页被卷去的左： document.body.scrollLeft<br>
网页正文部分上： window.screenTop<br>
网页正文部分左： window.screenLeft<br>
屏幕分辨率的高： window.screen.height<br>
屏幕分辨率的宽： window.screen.width<br>
屏幕可用工作区高度： window.screen.availHeight<br>
屏幕可用工作区宽度： window.screen.availWidth<br>
 <br>
<br>
JQuery:<br>
<br>
$(document).ready(function(){<br>
alert($(window).height()); //浏览器当前窗口可视区域高度<br>
alert($(document).height()); //浏览器当前窗口文档的高度<br>
alert($(document.body).height());//浏览器当前窗口文档body的高度<br>
alert($(document.body).outerHeight(true));//浏览器当前窗口文档body的总高度 包括border padding margin<br>
alert($(window).width()); //浏览器当前窗口可视区域宽度<br>
alert($(document).width());//浏览器当前窗口文档对象宽度<br>
alert($(document.body).width());//浏览器当前窗口文档body的宽度<br>
alert($(document.body).outerWidth(true));//浏览器当前窗口文档body的总宽度 包括border padding margin<br>
}<br>
<br>
