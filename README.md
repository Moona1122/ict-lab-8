# ict-lab-8
<!DOCTYPE html>
<html>
<head>
   <meta name="viewport" content="width=device-width", initial-scale="1.0">
   <link rel="stylesheet" href="style.css">
   <title>Personal portfolio</title>
   
</head>
<body>
   <!-- Header section -->
   <div class="header">
      <nav>
         <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="#">ABOUT</a></li>
            <li><a href="#">PROJECTS</a></li>
            <li><a href="#">SERVICES</a></li>
            <li><a href="#">CONTACT ME</a></li>
            <li><button type="button"class="button-gfc">Get Free Consultant</button></li>
            <li><button type="button" class="button-cv">DOWNLOAD CV</button></li>
         </ul>
      </nav>

      <!-- Body section -->
      <div class="body">
         <p class="demo1">GET EVERY SINGLE SOLUTIONS.</p>
         <h1>Hello <br> I'm Maimoona Habib</h1>
         <p class="demo2">From concept to deployment, I bring ideas<br> I specialize in guiding concepts through every stage of development <br>and deployment as a flexible and adept full-stack developer....</p>
         <button type="button" class="button-lrn">LEARN MORE</button>
         <button type="button" class="button-hire">HIRE ME</button>
      </div>

      <!-- Image section -->
      <div class="image">
         <img src="imggg.jpg">     
      </div>
      <button id="downloadButton">Download CV</button>

      <script>
          // Function to trigger the download
          function downloadResume() {
              // Replace 'cv.pdf' with the actual name of your PDF file
              var pdfUrl = 'cv.pdf';
      
              // Create a link element
              var link = document.createElement('a');
      
              // Set the href attribute to the PDF file path
              link.href = pdfUrl;
      
              // Set the download attribute with the desired filename
              link.download = 'cv.pdf';
      
              // Append the link to the document
              document.body.appendChild(link);
      
              // Trigger a click event on the link to start the download
              link.click();
      
              // Remove the link from the document after the download
              document.body.removeChild(link);
          }
      
          // Add a click event listener to the button
          document.getElementById('downloadButton').addEventListener('click', downloadResume);
      </script>
   </div>
</body>
</html>
