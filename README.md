<h1> Creating a Speech to Text Converter Website</h1> 

This is the documentation on how I create a basic tool that can convert speech to text. The final website can be seen in the file "tool.html". The basic feature of the website are below :

<ul>
  <li>The user is able to turn the tool on or off </li>
  <li> The user is able to have 2 options to select from : convert while you speak and convert after you speak</li>
  <li> The user is able to save the speech that they have created into a permanent box </li>
</ul>

 The picture below shows the final website that was created. 
 
 Figure 1 - Website 
<img src="Final_Website.JPG"> 

<h2> Step 1 - Create the Layout - HTML/CSS </h2> 

I first created a simple layout with one container and all further tools added within that container.  

Figure 2 - Simple HTML Structure 

<img src="html_layout.JPG">

<h2> Step 2 - Create the Non Supporting Warning </h2> 

The tools that I used to help recognise the speech is the SpeechRecognition Web Speech API. However, this API is not supported by some browsers, therefore a script had to be created to inform the user whether their browser is able to support the API. 

The script below checks to see if the browser is able to add the SpeechRecognition object and if it can not, then the Javascript will remove the "hidden" tag from the CSS of the hidden container and so show the warning that was created in the html layout.


Figure 3 - Support Javascript
<img src="support_javascript.JPG">

<h2> </h2>


