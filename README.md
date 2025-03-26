<!-- How To Edit And Host The Portfolio Website -->


**Directory Structure**
📂 data
 ├── personal-data.js      # Personal information data
 ├── projects-data.js      # Data for projects
 ├── services-data.js      # Data for services

📂 images-and-icons
 ├── icons                 # Icon assets
 ├── images                # General images

📂 script
 ├── about.js              # About section script
 ├── main.js               # Main script file
 ├── projects.js           # Projects section script
 ├── render-contents.js    # Dynamically renders content
 ├── top-nav.js            # Navigation bar script

📂 style
 ├── sections-style        # Section-specific styles
 │   ├── about-section.css
 │   ├── contact-section.css
 │   ├── projects-section.css
 │   ├── services-section.css
 ├── animation.css         # Animation styles
 ├── footer.css            # Footer styles
 ├── global.css            # Global styles
 ├── laning-content.css    # Landing page styles
 ├── profile.css           # Profile section styles
 ├── top-nav.css           # Navigation bar styles

📄 LICENCE.txt             # License agreement and terms  
📄 page.html               # Main HTML file
📄 README.md               # Project documentation



**HOW TO CHANGE AND UPDATE CONTENT**

🔹 Modify Data:

Navigate to the data folder and update the respective JavaScript files:

personal-data.js → Modify personal information.

projects-data.js → Update project details.

services-data.js → Change service offerings.

📌 Updating Images and Icons:
If you want to change your images or icons, make sure to place them in the appropriate folder. There are comments in the code specifying where each type of image or icon should go.

All updates will be automatically reflected since they are dynamically rendered in render-contents.js.

🎨 Update Styles:

Open the style folder.

Modify the CSS files to adjust the website’s design and appearance.

⚠️ Notes:
✅ Do not remove render-contents.js, as it dynamically loads data from the data folder.
✅ Ensure that the JavaScript object structures in the data folder remain consistent to prevent errors.


**HOW TO RUN THE PROJECT IN LIVE SERVER**

  1: Using VS Code Live Server Extension (Recommended):
  2: Open VS Code and go to the Extensions marketplace.
  3: Search for Live Server and install the extension.
  4: Open the project folder in VS Code.
  5: Locate page.html in the file explorer.
  6: Right-click on page.html and select "Open with Live Server".

  Your default web browser will automatically open and display the website.


**HOW TO HOST THE WEBSITE**
📌 Watch the tutorial here👉 [Easy Way to Host Your Website](https://youtu.be/3e_FVE4piEM?si=Zs3fJf6QOZm2LnBW)


