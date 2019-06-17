---
layout: post
categories: blog
title: this is a blog
---
hello world

```
...  
// inside ChildComponent  
shouldComponentUpdate(nextProps) {    
  return this.props.message !== nextProps.message;  
}  
...
```
