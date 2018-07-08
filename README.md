# sharetoworkplace
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
