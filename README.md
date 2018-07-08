# sharetoworkplace
<img src='https://camo.githubusercontent.com/f97907b97b04c107ffc50377a92ec426ddad8785/68747470733a2f2f7374617469632e78782e666263646e2e6e65742f727372632e7068702f76332f79472f722f4d5a7a7365764c376f34632e706e67'>

Share to Workplace by Facebook Bookmarklet

I created the Workplace bookmarlet to enable easy one button publishing of any web page from a web browser to Workplace. This will allow greater levels or particpation and adoption by making it rediculously easy to post new and engaging content to Workplace.

This is the raw javascript that enables the bookmarket shortcut to work. Create a new shortcut on the Bookmarks bar and copy and paste the code below or from the share.js file in to the URL field. Give it a name like 'Share to Workplace' and save.

Copy the code<br>
<code>javascript:(function(){
url = 'https://work.facebook.com/sharer.php?display=popup&u=' + window.location.href;
options = 'toolbar=0,status=0,resizable=1,width=626,height=436';
window.open(url,'sharer',options);
})();</code>

<a href='https://github.com/lyletedwards/sharetoworkplace/blob/master/share.js'>Link to JavaScript Code</a>

Paste the code and Save<br>
<img src='https://github.com/lyletedwards/sharetoworkplace/blob/master/bookmarkletsettings.png' height='50%' width='50%'>
<p>
You are ready to go<br>
<img src='https://github.com/lyletedwards/sharetoworkplace/blob/master/bookmarkletbar.png' height='30%' width='30%'>

<a href='https://github.com/lyletedwards/sharetoworkplace/wiki'>Workplace bookmarlet Wiki Page</a>


Lyle Edwards 

Originally Published
Dec 02, 2017
