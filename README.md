infograf1
=========

&lt;!doctype html> &lt;html   xmlns:fb="https://www.facebook.com/2008/fbml"> &lt;head> &lt;meta charset="utf-8"> &lt;title>Fan Event&lt;/title> &lt;script src="http://code.jquery.com/jquery-  1.6.2.min.js" type="text/javascript">&lt;/script> &lt;/head> &lt;body> &lt;div id="fb-root">&lt;/div> &lt;script   src="http://connect.facebook.net/ko_KR/all.js">  &lt;/script> &lt;script>     FB.init({       appId : '394799607246314',       status : true,       cookie : true,       oauth: true     });      function sendRequest() {       FB.ui({method: 'apprequests',         title: "이 페이지를 친구들에게 알려 주  세요.",         message: '새로운 이벤트가 있습니다.'       }, requestCallback);     }          function requestCallback(response) {       // Handle callback here     }   &lt;/script>    &lt;p>       &lt;a href="#" onclick="sendRequest();   return false;">친구에게 알리기&lt;/a>   &lt;/p> &lt;/body> &lt;/html>	