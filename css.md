# CSS

### selectors

```css
.header {

}
.class{
	/* basic styles */
	height: 1rem;
	width: 1rem;
	margin: 1rem 2rem 1rem 2rem;
	margin-right: 2rem;
	padding: 1rem;
	border: 1px solid white;
	border-radius: 100%; /* will create a circle */

	background: magenta;
	background: #FFAAFF; 
	background: rgb(255, 255, 255);
	background: rgba(255, 255, 255, 0.5) /* red, green blue, opacity (0 to 1) */
	color: green;

	font-size: 1rem; 
	font-family: Helvetica, Arial;
	font-weight: bold;
	text-align: center; 

	display: flex;
	position: relative; 

}
```

### hover

```css
.class{
	background: white;
}
.class:hover {
	background:blue;
}
```

### flexbox
```css
.class {
	display: flex;
	flex-direction: row;
	align-items:flex-start;
	justify-content: flex-start;
	flex-wrap: wrap;
}
 


