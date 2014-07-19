###Changelog for WP-Forge###

####v5.3.1 ####
* Updated to the latest version of Foundation v5.3.1
* removed unnecessary declaration from lines 393 and 394 of style.css - Thanks Hash Varsani
* Added new sitemap.php file - users can now create a sitemap page.
* Users can control how many posts are displayed on the sitemap page in the theme customizer, under the "Posts" section
* Updated wp-forge.po file, also removed es_ES.po file. The author of that language files stated there were issues and asked for it to be removed and he will replace.

####v5.3.0####
* Updated to the latest version of Foundation v5.3.0
* Minimized font css a little more
* Added Spanish Spanish Translation - Thanks to Alfonso Correas

####v5.2.3.1a####
* Seems in my haste to push out a fix for the Off Canvas issue, I forgot to change the version number in all of the files of WP-Forge. My apologies.

####v5.2.3.1####
* Added data-offcanvas attribute to line 13 of content-off_canvas.php - Seems Foundation added this to Off Canvas in 5.2.3

####v5.2.3####
* Updated to latest version of Foundation 5.2.3
* Added 'none' to the options for Background Position in the theme customizer.
* Changed the default text of the menu fallback function
* Updated normalize.css to 3.0.1 http://necolas.github.io/normalize.css/
* Added 'contain' to the Background Size option in customizer.
* Added Font-Awesome back into the mix. The shortcode plugin I am working on will use this font as well.
* Combined all font css into one file.
* Social menu icons are now handled by Font-Awesome. Font-Awesome provides a larger array of social icons.
* Added Russion Translation - Thanks to Andriy https://github.com/helirexi

####v5.2.2.4####
* Removed all styles back to their own style sheets and called them appropriately through functions.php - Apparently this was causing WP-Forge to display incorrectly in IE and FF.

####v5.2.2.3####
* Moved all css files to style.css
* Removed Fontawesome icon set and added the Genericons font http://genericons.com/#wordpress
* Changed the way the information for posts is displayed. Moved categories a post is assigned to above the title. Moved the post date, author and comments directly under the title. Tags are still listed after the post as well as the edit button that appears when the admin is logged in.
* Adjusted the social menu css to reflect the Genericons font.
* Moved the fonts folder into the inc folder
* Github versions of WP-Forge are now be tagged. This will allow end users to revert to previous releases of WP-Forge.
* Changed the appearance of the author information area - This will provide a more consistent look across different platforms. I didn't like the way it was appearing on smaller screens.
* Fixed issue with the post title being displayed as a link in single post view.

####v5.2.2.2####
* Added support for the Github Updater from Andy Fragen https://github.com/afragen/github-updater - You will now be able to update WP-Forge from within WordPress itself. You need to download and install the Github Updater.

####v5.2.2.1####
* Changed the max-width of rows in foundation.css from 62.5rem to 100%. Changed the max-width of #wrapper in style.css to 64rem (this is equivilant to 1024px based on 16px font size). This change will make it easier for users to change the width of the theme to whatever they like, even to full width.
* Removed the background color from rows. This is not needed as the background color of the wrapper element is white.
* Added function that links all post thumbnails to the post permalink.
* Added html5 shim to header (seems prevalent in WordPress themes)
* Added function that wraps inserted images in posts/pages with figure and figcaption. (thanks Tommie Landstrom)
* Corrected word-wrap and overflow-x issue with <pre> element. 
* Added data-options="mobile_show_parent_link: true" to top-bar. This will now display the parent link in mobile view. See http://foundation.zurb.com/forum/posts/809-top-bar-parent-links for more details (again thanks Tommie Landstrom)
* Moved Modernizr to load after jQuery

####v5.2.2####
* Updated to Foundation v5.2.2 (released on Friday 04/04/2014) - View changes made by Foundation via commit https://github.com/zurb/foundation/commit/520ea11dfe818691dd70cdb5c5ed5907e5e64168
* Removed the default values in the Background Section of the theme customizer.
* Added "background-size" section to Background Section of the theme customizer. This will allow users to set a full width image as the background of the site without a plugin. Read more about the "background-size" attribute http://www.w3schools.com/cssref/css3_pr_background-size.asp
* Removed background color from style.css and foundation.css - The default color will now be white. This will allow the user to set the initial color from within the theme customizer.
* Added all Foundation media queries to end of style.css - This is so users do not have to search for these in the actual Foundation Docs.
* .gitkeep file added to images folder. Thanks to baringji https://github.com/baringji
* Starting with this release main version will be updated to include minor patch version, i.e., current version is 5.2.2, if minor changes are made, the version will be appended to reflect 5.2.2.1 and so on.
* Updated language file.