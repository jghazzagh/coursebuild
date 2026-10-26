MCC Course Builder: hosting notes
=================================

Upload these files to the same folder on your web host (for example, the
root of the GitHub Pages repository):

  index.html             Home
  templates.html         Page templates
  coursebuilder.html     Page Builder
  building-blocks.html   Block Guide
  widget-builder.html    Widget Builder
  support.html           Help
  mcclogoidi.png         Logo used in the header of every page

Keep the filenames unchanged so the navigation links and site search keep
working. Set index.html as the folder's default page.

Each page carries its own styling and scripts, so no other CSS, JavaScript,
or font files are needed. Fonts load from Google Fonts when available and
fall back to standard system fonts.

What the builders produce
-------------------------
The Page Builder and Widget Builder copy finished HTML to the clipboard or
download it as an HTML file. That HTML uses inline styles only.

Most Page Builder blocks work with Brightspace's HTML Source Editor on a
content page. A few blocks (Page glossary, Page progress tracker, Question
bank, Reflection journal, and Unlock next section) add one small script to
the page. Brightspace keeps that script on content pages but removes it from
Module Overviews, where those blocks fall back to a simpler version. In the
Page Builder, Page settings > Where will this page go? tells the builder
which kind of page you are making so it can warn you.

Updating the site
-----------------
Replace the changed HTML files and keep the rest. Faculty drafts are saved
in their own browsers and in the JSON files they download, so updating the
site does not affect their work.

Instructional Design & Innovation
McLennan Community College
