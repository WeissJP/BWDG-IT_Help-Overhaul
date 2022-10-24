# BWDG-IT_Help-Overhaul
This project was a complete overhaul of the existing IT Help menu that is pushed to all company PCs. It was hand written by myself in HTML5/CSS3 from the ground up. Since this project contains internal company information, all I can provide are screenshots and a description.
The previous version of these IT help files was in dire need of an update, so I volunteered to do it. I soon discovered it was still in HTML4, with little to no CSS (all of it inline), and convoluted user instructions. The folder structure was also a mess, with duplicate files, outdated documents, and additional HTML files that were not linked in the main help file. I then decided to perform a complete overhaul.

## Main Page
Pictured below is the main page; it includes a link to the company intranet, encouraging users to utilize self-help articles. Below that, there are three buttons for navigation within the local help pages. The leftmost button, "How to Contact IT Support", is a link to an internal Knowledge Base article giving instructions on contacting the IT help desk. The middle button, "Map Network Drives", takes the user to a sub-page (see section below). The rightmost button, "Map Office Printers", takes the user to another sub-page (see section below). The buttons turn a darker color when the user hovers their cursor over it. The header at the top of the page includes a home button to take users back to the main page, and appears on both sub-pages.

![Main Page](IT_Help_images/main_page.png?raw=true)


## Map Network Drives Page
Pictured below is the sub-page for mapping network drives. At the top are instructions for mapping a network drive (for security reasons, running batch files straight from the browser isn't allowed). Below that are buttons for each office that has a network drive; each button opens a batch file in a new browser tab. As with the burrons of the main page, these ones also darken when hovered over for easier visibility. The button grid utilizes flexbox layout for better compatibility across different screen sizes.

![Map Network Drives](IT_Help_images/network_map.png?raw=true)


## Map Office Printers Page
Pictured below is the sub-page for mapping office printers. It is functionally the same as the Map Network Drives page (including CSS), the only difference is the contents of the batch file. It is simply a command to open the print server at a given office in File Explorer, where users can then double-click on their desired printer to connect to it.
The second picture below shows the page as a smaller window, demonstrating the responsive design and the cursor hovering over a button. 

![Map Office Printers](IT_Help_images/printer_map.png?raw=true)
![Map Office Printers 2](IT_Help_images/printer_map_small_window.png?raw=true)



#### Note
I did not create the batch files for mapping the network drives and office printers. They already existed, and I consulted both my supervisor and colleague from the networking/server team on updating them.
