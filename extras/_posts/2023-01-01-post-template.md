---
#layout: landingpage # change default layout
title: Data Science
subtitle: A brief introduction
header_type: hero # hero, image or splash
header_img: https://picsum.photos/id/1018/2000/2000
categories: [Supervised Learning]
#date:   2023-01-01 12:00:00  # already defined in file name
last_modified_at: 2023-02-02
tags: [Data Science, Machine Learning, Deep Learning]
project_links:
  - url: https://en.wikipedia.org/wiki/Data_science
    icon: "fab fa-wikipedia-w"
    label: See on Wikipedia
#author:
#  name: Octocat
#  avatar: https://github.com/octocat.png
#  location: Pennsylvania, United States
#  links:                
#    - url: https://github.com/github/
#      icon: "fab fa-github"
#    - url: https://twitter.com/github
#      icon: fab fa-twitter
#    - url: https://github.com/facebook
#      icon: "fab fa-facebook"
#    - url: https://www.linkedin.com
#      icon: "fab fa-linkedin"
mathjax: true
show_comments: true
---

# Main Heading
This is a **link**: [markdown](http://markdowntutorial.com/).

## Secondary heading

Table:
 
| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |
 

Show some image:
![Image](http://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

Some code chunk:
~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

Code with syntax highlighting:
```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

### Example of a quote

> **MSE** (also known as '*Mean Squared Error*'): You can find more information at Wikipedia.
>
>
> From [Wikipedia](https://en.wikipedia.org/wiki/Mean_squared_error)
> {: .blockquote-footer }


### How to append content of html file
**Current tags:**
{% if page.show_bottomnavs -%}
{% include components/tags.html -%}
{% endif -%}

Stochastic Learning Descent


### Testing Mathjax:
$$E=mc^2$$