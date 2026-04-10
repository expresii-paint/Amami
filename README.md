# Amami Inker
Amami Inker is a web app that converts SVG curves to Expresii Paint strokes. It can export to an .XST (Expresii Stroke) file, or send the generated stroke commands directly to Expresii Paint app.

It looks like this:
![Demo Animation](./AmamiDemo.gif)


## To run the stroke commands
You can drag the generated .XST file onto Expresii to load the stroke commands. A stroke recorder window would appear. Or, you can press the 'Send' button from the web app after you generate the stroke commands. You need to enable web API service from Expresii Paint app. This uses port 9000. You can even send the commands to a remote host (more on this later).

