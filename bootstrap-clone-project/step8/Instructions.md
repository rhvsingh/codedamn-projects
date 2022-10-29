Step 8:

	Now we will work on styling the content section in the step.
	This will also be going to contain two parts- 
		1. Desktop design.
		2. Mobile design.
		
	First work on mobile design,
	
	#content {
		position: relative;
		color: #fff;
		display: flex;
		align-items: center;
		justify-content: center;
	}

	#content::before {
		position: absolute;
		content: '';
		background-color: rgba(0, 0, 0, 0.85);
	}
	
	Hint: use z-index: -1;
	
	Paragraph inside the content section, max-width: 40ch;
	
	Button color: #aaa;
	Button background-color: rgb(22, 58, 58);
	
	#content p {
		max-width: 40ch;
	}
	
	#content button {
		background-color: rgb(22, 58, 58);
		color: #aaa;
	}
	
	Now the desktop part,
	
	@media screen and (min-width: 992px) {	
		#content {
			height: 100vh;
			width: 65vw;
		}
		#content::before {
			transform: skewX(-9deg);
			transform-origin: top right;
		}
		#content>div {
			max-width: 40rem;
		}
		#content h1 {
			max-width: 400px
		}
	}
	
	Other properties you try and add on your own.