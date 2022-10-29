Step 3:

	In this step, We will be going to create a video section.
	Give it an id of that section you have created for the video.
	And inside the section, use the video HTML tag to add a video to the web page,  
	and add the following attributes in the tag:
		autoplay muted loop
		
	By the way, you can find the video inside the assets folder. So you just have to link it that's it.
	And also give the video tag an id.
	
	For example: 
	
	<div id="video-container">

        <video id="video-player" autoplay muted loop>
            <source src="assets/pixel_video.mp4" type="video/mp4">
        </video>

    </div>