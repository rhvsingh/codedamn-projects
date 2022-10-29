Step 7:

	Now we will work on styling the social section in the step.
	It will be going to contain two parts- 
		1. Desktop design.
		2. Mobile design.
	Now you have to use media query in this step in order to make this webpage responsive as well.
	
	For a minimum width of 992px: 
		Give #socials position: absolute property and width: 200px.
		Add use display: flex, align-items: center, justify-content: center
		In socials, li use display: block.
	
	Other properties you try and add on your own.
	
	For example: 
	
	For mobile design:-
	
		#socials {
			position: relative;
		}

		#socials ul {
			list-style: none;
			padding: 0;
		}

		#socials li {
			display: inline-block;
			background-color: rgba(0, 0, 0, 0.85);
			color: #fff;
		}
		
		
	This part is for desktop design:-
	
	@media screen and (min-width: 992px) {
		
		#socials {
			position: absolute;
			widht: 200px;
			display: flex;
			align-items: center;
			justify-content: center;
		}
		#socials li {
			display: block;
			margin: 2rem;
			padding: 1.4rem 1.6rem;
		}
		.fa-facebook {
			left: 2px
		}
		
	}