---
layout: page
title: Tutorials
author: Nobita
---

Nothing but just some alternate of Lorem ipsum xD  

`_site` stores our finished, final compiled version of our (static?)website.  

The path within the scope attribute (inside the defaults tag in `_config.yaml`) tell us to which file this defaults front matter apply to.

#### Layout:
The minima theme (the default one) has 2 files(or many)- 
 - Post and 
 - Page 
##### which defines the layout for the post and page on our site.  


To access variables within the layout

Syntax:  `layout.<variable-name>`

viz., `page.author`


3 types of variable calling.
-site.<>  

-layout.<> 

-page.<>


#### A for loop in HTML  
##### I told you all na.... that `html` **is** a _progrmaing language_ .  xD

{% highlight html %}
{% for post in site.posts %}
	{{ post.title }} 
{% endfor %}
{% endhighlight %}

### Acknowledgement: 
#### Mike Dane Youtube Series on jekyll
[MikeD][Giraffe]   

#### Dipan Da 


#### Aryan 


[Giraffe]: https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB