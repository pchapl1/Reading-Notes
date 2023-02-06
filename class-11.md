Its important to think giving users control over playback.  It will also help to utilize grid with flexbox and move elements are the page easier.  And another important thing to keep in that i never really considered before was responsive images and bandwith.

### Explain how the ability to use video and audio on the web has evolved since the early 2000s.
    - audio and video were made possible by flash and silverlight back then but have now been replaced by html native elements that are more secure like <video> and <audio elements.>
    source: https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content

### Describe the use of the src and controls attributes in the <video> element.
    - the src attribute provides a path to the source of the video you are trying to display
    - control attribute gives usersthe ability to control the playback
    source: https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content

### Why is it important to have fallback content inside the <video> element?
    - in case the browser being used doesn't support the <video> element

### How does Grid layout differ from Flex?
    - grid is all about rows and columns.  flex has a one dimensional flow where as grid is does not.  

### Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
    - grid container is the parent element of grid items
    - grid item are the children of the grid container
    - grid lines are the dividing lines that make up the structure of the grid and can be either horizontal or vertical


### Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
    - embedding large images on small screens is a waste of bandwith because they have to download large images.  
### Define the following <img> attributes srcset and sizes. Write an example of how they are used.
    - srcset defines the images we will allow the browser to choose between and what size each image is.  
    - sizes defines a set of media conditions and indicateds what image size would be best to choose.  

    <img
        srcset="elva-fairy-480w.jpg 480w, elva-fairy-800w.jpg 800w"
        sizes="(max-width: 600px) 480px,
         800px"
        src="elva-fairy-800w.jpg"
        alt="Elva dressed as a fairy" />

    source: https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images

### How is srcset more helpful for responsive images than CSS or JavaScript?
    - because by the time you js detects the viewport width, both the original image wouldve loaded along with any other images