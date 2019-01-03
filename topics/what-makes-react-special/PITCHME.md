## What makes React special?

+++

Companies using React:

- Facebook |
- Netflix |
- Paypal |
- Twitter |
- Yahoo |

+++

<iframe
	class="jsfiddle"
	src="https://jsfiddle.net/mjw56/prmb65L0/embedded/js,html,css,result/dark/"
	allowfullscreen="allowfullscreen"
	frameborder="0">
</iframe>
<br/>

+++

What do you notice?

- We are creating our own HTML-type elements |
- The HTML is within the JavaScript (JSX) |

+++

### What React gives you

+++

### React is only the view layer

- React components are just functions that accept input and return UI output (JSX is sugar on top of JavaScript functions to make them look like HTML)
- React components can internally have their own state, but it's opt-in for every component

+++

### React uses a virtual DOM

- React maintains its own copy of the DOM in JavaScript |
- Only changes are sent to the browser to be updated |
- Calling setState in a component, it only re-renders from component called and all children recursively

+++

### React focuses on separation of concerns rather than separation of technologies

- HTML and JS are together |
- They actually work together |

+++

### React gives you readable, maintainable code

- Everything is a component |

+++

### Resources

- [How I learned to stop worrying and love React](https://firstdoit.com/how-i-learned-to-stop-worrying-and-love-react-4e22b0bb6c2a)
