---
layout: post
categories: blog
tags: 'test, hello, blog'
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

```
class MyComponent extends React.Component {
  shouldComponentUpdate(nextProps, nextState) {
    return !shallowEqual(this.props, nextProps) || !shallowEqual(this.state, nextState);
  }
  ...
}
```
