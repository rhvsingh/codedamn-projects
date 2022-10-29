Step 6:

	Now, our HTML structure is complete.
	We will work on the style part from now.
	So get ready,
	You have already set up basic styles.
	
	Let's first work on the video player section
		So as you can see in the design video is in the background.
		For that, you have to give the video section a positioning absolute property.
		And add other relevant properties to make it look similar to the design.
		
		Use a pseudo selector in the video section for creating an overlay type of effect.
		Use background-color : rgba(42, 85, 85, 0.7); to get exaclt same effect.
	
	For example: 
	
		#video-player {
			position: absolute;
		}

		#video-container::before {
			position: absolute;
			content: '';
			background-color: rgba(42, 85, 85, 0.7);
		}
		
	I have removed other properties. Now it's your work to figure out what to add to make it work.
	