## Overview
We are creating a browser action Chrome extension. We'll put an icon in the URL bar panel.
![Our app icon shown in the URL bar panel](designs/comps/Browser%20Action%20Placement%20Comp.png?raw=true)

When a user clicks our icon, a panel will be displayed. We'll use a wizard on the panel to gather all the user's decisions and download the file. Firstly, the user must decide whether to take the current viewframe or the entire page.
![Step 1 of our wizard](designs/comps/Step%201.png?raw=true)

Next, the user selects annotation values.
![Step 2 of our wizard](designs/comps/Step%202.png?raw=true)

The user's choices will be included in the final image.
![Output example including annotations](designs/comps/Sample%20Output%20Comp.png?raw=true)

Lastly, the user chooses a filename and is shown the file size. They may choose to optimize the file to reduce it below the USPTO threshold.
![Step 3 of our wizard](designs/comps/Step%203.png?raw=true)

Finally, clicking the download button should begin the browser download dialog with the user's chosen filename as the suggested name.