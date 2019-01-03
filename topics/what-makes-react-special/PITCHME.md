## What makes React special?

+++

<iframe
	class="jsfiddle"
	src="https://jsfiddle.net/mjw56/prmb65L0/embedded/js,html,css,result/dark/"
	allowfullscreen="allowfullscreen"
	frameborder="0">
</iframe>
<br/>

+++

- We are creating our own HTML-type elements |
- The HTML is within the JavaScript (JSX) |

+++

### What React gives you

+++

### React is only the view layer

- React components are just functions that accept input and return UI output (JSX is sugar) |
- React components can internally have their own state (opt-in) |

+++

### React uses a virtual DOM

- React maintains its own copy of the DOM in JavaScript |
- Only changes are sent to the browser to be updated |
- Calling setState only re-renders from call site and below |

+++

### React focuses on separation of concerns rather than separation of technologies

- HTML and JS are together |
- They actually work together |

+++

### React gives you readable, maintainable code

- Everything is a component |

+++

### Resources

- [Tutorial: Intro To React](https://reactjs.org/tutorial/tutorial.html)
- [Making Sense of React Hooks](https://medium.com/@dan_abramov/making-sense-of-react-hooks-fdbde8803889)
