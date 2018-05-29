# Web-Development-Template
Create Web Projects with git workflow -using nodejs,npm,gulp


	Folders & function           * - auto-generated.
-------------------------------------------------------------------------------------
  app/assets/images/ ->add website files here
  app/assets/icons/  ->add (svg) icons of the website
 
 *app/assets/sprites/	-> auto-generated from svg of icons
  
  app/assets/styles/base  ->add base style files for the website
		|- _global.css -> add global style
		|- _mixins.css -> global media query for different target devices(mobile,tablet,desktop,large) .
		|- _variables.css -> global variables
  app/assets/styles/styles.css -> import for all the base and module files.
 
 *app/temp/styles/styles.css -> auto-generated based on the above file.(this file must be linked in the html for css styling).
  
<!-- For developers -->
  gulp/tasks/sprites.js  -> [gulp icon] task for sprites (svg files)
  gulp/tasks/styles.js   -> gulp task for apply postcss filters to modules and base files.
  gulp/tasks/watch.js    -> [gulp watch] task for creating the final stylesheet under temp folder.
  gulp/templates/sprite.css -> template to auto-generate _sprite.css and sprite.svg files


