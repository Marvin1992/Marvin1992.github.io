---
layout: post
title: Custom Elements
---

## Issues with Custom Elements

<p>
With Custom Elements, Shadow Dom and Templates, a lot of power is given to the client side. For instance that templates have to be called in order to be active is a great concept that makes loading images, videos or other loadable content much easier due to its asynchronical nature meaning that it is not rendered and only accessed via javascript on demand. Using templates to load certain content areas of a webpage will make web design much easier. For instance, if one was to design an image gallery with 8 images per view area, one could just put these images into a template and load or exchange these images with another template holding images whenever wished.
</p>
<p>
Another great thing about Custom Elements is their reusability. After having coded a custom element with javascript, one only needs to reference it in the HTML using {% highlight html %} <customElementsName>...</customElementsName> {% endhighlight %}. As soon as custom elements will be fully intregrated into the web, the way web pages or web applications will be designed and USED will change completely. Just imagine how much time and coding is spent on for instance having a search bar connected with php to a database in order to retrieve items. What if this search bar was wrapped in a custom elements called {% highlight html %} <x-searchbar> {% endhighlight %}  and anyone could simply add this little junk of code to its own webpage to have a working search bar. This might be not the best example, but it still stresses the power of custom elements. Of course one could argue whether future web design will only consist of putting together custom elements and indeed that person might be right, but imagine how much more complex web pages would be: Google could work on a voice recognizing custom element that is implemented into Amazons webpage for example, making Amazon search speech only. Or amazon might want to display its content in a certain manner and ask a different company for their custom element. Of course they might need to spent money on these elements, but they would also save a lot of programming time. And time means money in return. 
</p>
<p>
Problematic might be the actual implementation, because the custom element as the name suggests might be too customized to implement for a general purpose on somebody elses web application. But how general the custom element can be used, depends very much on the designer of the custom element. But web giants like Google will most likely find a way to keep their "custom" elements as general to use as possible in order to sell or export them to other companies.
</p>
