# LaTeX CV Template

This is a modern, stylish CV template created with LaTeX. It uses the **ModernCV** class for a clean and professional layout, featuring custom colors, icons, and a circular profile image with a shadow glow effect.

You can easily copy this LaTeX code to [Overleaf](https://www.overleaf.com/) and customize it to create your own CV. Change the background, update the content, and make it your own!

## Features

- Customizable layout with ModernCV style
- Circular profile picture with shadow glow effect
- Sectioned for work experience, education, skills, and more
- Easy to edit and update
- Clean, professional, and modern design

## How to Use

1. **Open Overleaf:**
   Click on the link below to open the project in Overleaf:
   
   [Open in Overleaf](https://www.overleaf.com/latex/templates/moderncv-cv-template/nhzrrwwwznqp)

2. **Copy the LaTeX code:**
   If you already have an Overleaf account, simply copy this LaTeX code to your own project or fork the template from the Overleaf link.

3. **Change the Background:**
   You can easily change the background image by uploading your own image file and updating the `background.jpg` in the code:

   ```latex
   \backgroundsetup{
     scale=1,
     color=black,
     opacity=0.03, % Adjust the opacity as needed
     angle=0,
     position=current page.south,
     vshift=10cm,
     hshift=0cm,
     contents={\includegraphics[width=\paperwidth,height=\paperheight,keepaspectratio]{background.jpg}}
   }


## Preview the Result:
Here is a preview of the final CV layout, showing a sample background and layout:

![CV Preview](https://github.com/DabanAbdullah/LatexCV/blob/main/cv-screenshot.png)