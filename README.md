# List of Awesome Bookmarklets :rocket:

> How to use? 
1. Copy the code.
2. Drag & Drop into the Bookmark bar. [//]: # (Rename it (Optional))
3. Done! :tada:  

- ## Instant Web Proxy

```javascript
javascript:void(open('https://translate.google.co.in/translate?hl=en&sl=sq&tl=en&u='+location.href));
```

- ## 1-Click Video Downloader
```javascript
javascript:void(open('https://tbvd.herokuapp.com/redirect?url='+encodeURIComponent(location.href)));
```

- ## 1-Click Audio Downloader
```javascript
javascript:void(open('https://tbvd.herokuapp.com/video?url='+encodeURIComponent(location.href)+'&audio=on'));
```

- ## 1-Click PDF Convertor
```javascript
javascript:void(open('https://v2.convertapi.com/web/to/pdf?download=attachment&secret=5LIWRmsz4uKJCITZ&url='+encodeURIComponent(location.href)));
```

- ## 1-Click Photo Convertor
```javascript
javascript:void(open('https://v2.convertapi.com/url/to/jpg?download=attachment&secret=5LIWRmsz4uKJCITZ&url='+encodeURIComponent(location.href)));
```

# **Website**
- ## Website Analyzer (Traffic Statistics & Market Intelligence)
```javascript
javascript:void(open('https://www.similarweb.com/website/'+encodeURIComponent(location.href)));
```

- ## Website Quick Editor
```javascript
javascript:document.body.contentEditable = 'true'; document.designMode='on'; void 0
```

- ## Website Time Machine (Wayback Machine)
```javascript
javascript:void(open('http://quirktools.com/screenfly/#u='+location.href+'&w=640&h=480&a=4&s=1'));
```

- ## Similar Website Finder
```javascript
javascript:void(open('https://www.google.com/search?q=related:'+location.href));
```

- ## Website Whois Lookup
```javascript
javascript:void(open('http://whois.domaintools.com/'+encodeURIComponent(location.href)));
```

- ## Website Source Code Viewer
```javascript
javascript:void(open('view-source:'+encodeURIComponent(location.href)));
```

- ## Website Speed Test
```javascript
javascript:void(open('https://developers.google.com/speed/pagespeed/insights/?url='+encodeURIComponent(location.href)));
```

- ## Website Build with (Websites are built with what)
```javascript
javascript:void(open('https://builtwith.com/?'+encodeURIComponent(location.href)));
```

- ## Website Auto CSS Selector Generator
```javascript
javascript:(function(){var s=document.createElement('div');s.innerHTML='Loading...';s.style.color='black';s.style.padding='20px';s.style.position='fixed';s.style.zIndex='9999';s.style.fontSize='3.0em';s.style.border='2px solid black';s.style.right='40px';s.style.top='40px';s.setAttribute('class','selector_gadget_loading');s.style.background='white';document.body.appendChild(s);s=document.createElement('script');s.setAttribute('type','text/javascript');s.setAttribute('src','https://dv0akt2986vzh.cloudfront.net/unstable/lib/selectorgadget.js');document.body.appendChild(s);})();
```

- ## Responsive Website Tester
```javascript
javascript:void(open('http://quirktools.com/screenfly/#u='+location.href+'&w=640&h=480&a=4&s=1'));
```

# **Misc.**
- ## Add to Feedly
```javascript
javascript:void(open('https://feedly.com/i/subscription/feed/'+encodeURIComponent(location.href)));
```

- ## Add to Pocket
```javascript
javascript:(function(){var e=function(t,n,r,i,s){var o=[3139821,1691404,3942330,4280155,4867141,1525736,3824752,3937958,1747379,3644113];var i=i||0,u=0,n=n||[],r=r||0,s=s||0;var a={'a':97,'b':98,'c':99,'d':100,'e':101,'f':102,'g':103,'h':104,'i':105,'j':106,'k':107,'l':108,'m':109,'n':110,'o':111,'p':112,'q':113,'r':114,'s':115,'t':116,'u':117,'v':118,'w':119,'x':120,'y':121,'z':122,'A':65,'B':66,'C':67,'D':68,'E':69,'F':70,'G':71,'H':72,'I':73,'J':74,'K':75,'L':76,'M':77,'N':78,'O':79,'P':80,'Q':81,'R':82,'S':83,'T':84,'U':85,'V':86,'W':87,'X':88,'Y':89,'Z':90,'0':48,'1':49,'2':50,'3':51,'4':52,'5':53,'6':54,'7':55,'8':56,'9':57,'\/':47,':':58,'?':63,'=':61,'-':45,'_':95,'&':38,'$':36,'!':33,'.':46};if(!s||s==0){t=o[0]+t}for(var f=0;f<t.length;f++){var l=function(e,t){return a[e[t]]?a[e[t]]:e.charCodeAt(t)}(t,f);if(!l*1)l=3;var c=l*(o[i]+l*o[u%o.length]);n[r]=(n[r]?n[r]+c:c)+s+u;var p=c%(50*1);if(n[p]){var d=n[r];n[r]=n[p];n[p]=d}u+=c;r=r==50?0:r+1;i=i==o.length-1?0:i+1}if(s==282){var v='';for(var f=0;f<n.length;f++){v+=String.fromCharCode(n[f]%(25*1)+97)}o=function(){};return v+'b100288614'}else{return e(u+'',n,r,i,s+1)}};var t=document,n=t.location.href,r=t.title;var i=e(n);var s=t.createElement('script');s.type='text/javascript';s.src='https://getpocket.com/b/r4.js?h='+i+'&u='+encodeURIComponent(n)+'&t='+encodeURIComponent(r);e=i=function(){};var o=t.getElementsByTagName('head')[0]||t.documentElement;o.appendChild(s)})()
```

# Bonus :sparkles:
- ## Instant Notepad
```
data:text/html, <html contenteditable>
```

- ## Instant Notepad (Dark)
```
data:text/html;charset=utf-8, <title>Notepad (Nightmode)</title><body contenteditable style="font-family: DejaVu;font-weight:bold;background:%231E1E1E;color:%23FFFFFF;font-size:1rem;line-height:1.4;max-width:80rem;margin:0 auto;padding:2rem;" spellcheck="false">
```
