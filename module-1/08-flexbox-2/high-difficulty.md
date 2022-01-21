# Higher Level of Difficulty Flexbox
The code listed here is the solution from `flex-box.css`:

```css
.flex-container{
	display: flex;
	flex-wrap: wrap;
	width: 800px;
	justify-content: space-around;
	margin: 0 auto;
}

/* Middle-Left */
div p:nth-child(2){
	order: 3;
}

/* Bottom-Left */
div p:nth-child(3){
	order: 6;
}

/* Top Center */
div p:nth-child(4){
	order: 1;
}

/* Middle Center */
div p:nth-child(5) {
	order: 4;
}

/* Middle Bottom */
div p:nth-child(6) {
	order: 7;
}

/* Top Right */
div p:nth-child(7) {
	order: 2;
}

/* Center Right */
div p:nth-child(8){
	order:5;
}

/* Bottom Right */
div p:last-child {
	order: 8;
}
```