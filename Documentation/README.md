This folder contains all of the Documentation for our shared server. Make a separate folder for your teams specific part of the server. Be sure to include your .tex files so we can build documentation and better keep track of changes.

If you include any images in your documentation, they must be included with your .tex file when you push up to this branch so when we build documentation, the images are also included.

Each document will have a directory. Inside the directory, there will be a main &lt;
filename& gt;.tex file, a sections folder, a graphics folder, and other folders as necessary. The sections directory will contain .tex files for each section. These files should not have any preamble material;
the first line should be \section
{
  &lt;
  sectionname& gt;
} and it should only contain content for that section. Any graphics used need to be added to the graphics directory and included in &lt;
sectionname& gt;
.tex with a relative path in that
directory(e.g.an image with path graphics / mysection /
          image.png requires \includegraphics{
            mysection / image}) Changes will need to be made to& lt;
filename& gt;.tex to include the section file (e.g. \include{
  sections / &lt;
  sectionname& gt;}) and to reference necessary packages in the preamble.

Please use the standard indicated. Include you section in the sections directory and graphics in the graphics directory. Do not just copy a directory over for your section into the document root.
