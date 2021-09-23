The Simplest way to import an image in a react component. 

Let's say our image is in the same folder as our React component, then the import would look something like this.

```jsx
import Logo from “./logo.png”;
```

This will import the file logo.png and reference in the file as “Logo”. Now when you reference the img tag in project you want it to now look like this

```html
<img src={Logo}>
```
