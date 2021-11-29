**1) Introduction**  
https://github.com/haseebshaik00/FullStack_NodeJS_Live_March2020/blob/master/Lecture01/Intro_to_WebDev.pptx  
a) how the web works: servers, clients, ISPs, DNS, Datacenters  
b) web terminologies: protocols; addresses-ip,domain,mac; packets  
c) components of web: web pages, web sites, web servers, search engines  
d) how web technologies work?  
i) server   
ii) server frameworks : java(spring,play,jboss);python(flask,django,bottle);ruby-rails
  PHP(laravel,codeigniter);node.js(express,hapi.js)  
iii) client side technologies:  
  -- html for markup or structure  
  -- css(SASS and LESS) for styling   
  -- js(jquery,angular,react,backbone,knockout) for scripting and events  
  -- server side DB - RDBMS(MySQL,Postgres,Oracle,MS Databases) and NoSQL(MongoDB,CouchDB,Memcache,Redis)  
  -- client side storage - local Storage, session Storage, cookies, indexedDB, cache  
iv) types of websites : static, dynamic and responsive  
v) RESTful APIs : a contract between server and client, a way to communicate between backend and frontend using diff 
HTTP methods like GET, POST, PUT, DELETE, PATCH
vi) data exchange formats - json and xml  
e) Website design principles - reactive websites, single-page websites, MVC,MVP,MVMM and MV* architecture and web application framework  
f) latest developments - VirtualDOM, ShadowDOM, Sockets, Pub/Sub, Push Notifications, Browser Native APIs(Location, User Data)  
  

**2) HTML**  
a) html5 boilerplate and description of each element and attribute in it  
https://github.com/haseebshaik00/FullStack_NodeJS_Live_March2020/blob/master/Lecture01/html-basics/index.html  
b) normal text, tags - para"p-/p", break"br", italic "i-/i" or "em-/em", bold "b-/b" or "strong-/strong", underline"u-/u",
strikethrough text"s-/s", lists ("ul li-/li ul" ; "ol li-/li ol") and their types, type and start attribute can also 
be written https://github.com/haseebshaik00/FullStack_NodeJS_Live_March2020/blob/master/Lecture01/html-basics/lists.html, nested lists, anchor with href "a-/a" ~ adding target="_blank" opens link in a new tab https://github.com/haseebshaik00/FullStack_NodeJS_Live_March2020/blob/master/Lecture02/more-with-html/links.html ~ inner links : hreffing to the id scrolls the page to that section https://github.com/haseebshaik00/FullStack_NodeJS_Live_March2020/blob/master/Lecture02/more-with-html/inner-links.html, tables : https://github.com/haseebshaik00/FullStack_NodeJS_Live_March2020/blob/master/Lecture01/html-basics/tables.html  
c) Advance topics https://github.com/haseebshaik00/FullStack_NodeJS_Live_March2020/tree/master/Lecture02/more-with-html : iframes ~ use name attribute inside iframe to target them, image "img", video "video-/video" ~ attribute controls shows and manages the controls of the video ~ loop ~ autoplay ~ preload : auto, none, metadata, audio "audio-/audio" ~ have almost same attributes as the video tag     
d) block and inline elements ~ elements can be changed to one another changing the display attribute in CSS   
e) form https://github.com/haseebshaik00/FullStack_NodeJS_Live_March2020/blob/master/Lecture02/more-with-html/forms.html : names is mainly used to refer the elements where as id is mainly used by js, form elements : input "input" many types~password, email,number has min and max attributes too, color, file, checkbox, radio; date; textarea "textarea-/textarea" adjust size with rows and cols; select with options "select option-/option /select" ~ multiple attribute can also be use in this  
f) more form tags : button "button-/button" ~ type="submit" or "reset";  
g) form action="" The HTML form action attribute defines where to send the form data when a form is submitted in an HTML document.  
h) The method attribute specifies how to send form-data (the form-data is sent to the page specified in the action attribute). The form-data can be sent as URL variables (with method="get" ) or as HTTP post transaction (with method="post").  


**3) CSS**  
a) referred in the head tag using - <link rel="stylesheet" href="./style.css">    
b) used for styling texts, styling boxes and css layout  
c) selectors - type, class(.), id(#), universal(*), attribute exampls- input[disabled] or input[type=text]    
d) combinators - adjacent sibling selector(+), general sibling selector(~), child selector(>), descendent selector(" "), or(,)      
e) pseudo selectors used with an ":" - hover, active and focus  
f) more pseudo selectors - nth-child(), last-child, first-child, placeholder, link, visited  
g) id has 1:1 mapping whereas classses have many:many mapping  
h) body selector affects only body tag whereas * affects every tags individually    
i) overriding preference "id>class>element>*"  
j) if a body selector is written twice the second one will overwrite the same properties present in the first one  
k) css "inline-internal-external" file tags which are written last gets the higher priority and in this inline has 
the highest precedence   
**more css attributes**    
l) font-sizes : pt (typewriter font-10pt, browser default font-14pt); px; em(1em - width of character 'm' in default font size); vh-(1/100th of window height); vw-view width  
m) transform: skew, rotate, scale, translate  
https://www.w3schools.com/cssref/css3_pr_transform.asp    
n) box-shadow: color xaxis_shadow yaxis_shadow blur (all are in pixels), transition: seconds, border-radius: 10px     
transition : https://www.w3schools.com/cssref/css3_pr_transition.asp  
transition: property duration timing-function delay|initial|inherit;  
o) all transition is done with respect to origin where as transform is done with respect to last state  
p) keyframes and animations : "animation: name duration timing-function delay iteration-count direction" and animation-fill-mode    
q) 



## Notes  
1) provide same name for a particular section of radio buttons to select only one radio button  
2) to select a checkbox just by clicking the text you can use target the label "for" attribute with input's id  
3) giving height and width to inline elements is not possible so we make them inline-block  
4) 

https://www.coursehero.com/qa/wait/35803237/?question_id=35803237


## Writing README files on github
1) https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax  
2) https://levelup.gitconnected.com/github-readme-cheatsheet-617dff61fa23