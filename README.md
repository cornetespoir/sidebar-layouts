# sidebar-layouts
Easy and customizable layouts for themes.

How to install:

Step 1:
Copy this and paste it after <head> in your theme's code

 &lt;link rel="stylesheet" href="https://static.tumblr.com/svdghan/1EVqy89rf/sidebar-layout.css" /&gt;

Step 2: 
Copy the css in sidebar-options.css: https://github.com/cornetespoir/sidebar-layouts/blob/main/sidebar-options.css
  
and paste it before </style> in the code.

Step 3:
Add the "layout" class to your theme's container, "layout-sidebar" to the sidebar, and "layout-section" to the container for your posts.

Make sure your code follows this structure in order for it to work:

 &lt;div class="layout"&gt;

&ltdiv class="layout-sidebar"&gt
&lt!-- sidebar content goes here --&gt
&lt/div&gt

&ltdiv class="layout-section"&gt
  &lt!-- posts go here --&gt
  &lt/div&gt
