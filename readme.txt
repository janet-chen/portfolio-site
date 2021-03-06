################################################################################################

Readme for Creative | Bootstrap 4 Template - https://bootstrapious.com

################################################################################################

Hi,

thank you for downloading. Have fun and tell your friends about us ;)

Ondrej, Bootstrapious

---------------------
 CSS
---------------------

The theme stylesheet is css/style.default.css. If you want to make any changes,
you can do it here or better to override it in custom.css so you can update the original theme stylesheet if an updated is released.
Changing to another colour variant, is just a matter of replacing css/style.default.css with css/style.pink.css in index.html.

---------------------
 JavaScript
---------------------

Apart from the Bootstrap JS components, the majority of JS is located in /js/front.js.

---------------------
 CREDITS
---------------------

- Botstrap 4.1 - http://getbootstrap.com/
- Font Awesome 4.7 - http://fontawesome.io/
- more in credits.txt.

---------------------
 Changelog
---------------------

Version 2.0.1 - 2018/02/14
--------------------------
- updated: Bootstrap to 4.3.1
- updated plugins: PopperJs, Masonry

Version 2.0.0 - 2018/06/01
--------------------------
- remake and upgrade to Bootstrap to 4.1.1

---------------------
 LICENSE CONDITIONS
---------------------

You are completely free to use this template for your personal use or as a work for your client as
long as you keep the link at the template footer pointing to us and our partner.

If you would prefer removing the backlink from the theme footer, please donate (https://bootstrapious.com/donate)
to support themes' development. Suggested amount per template is $10.
Also, as a bonus for donors, I can provide you the SASS files for even easier template customization.
Drop me a line at hello@bootstrapious.com after donating.

However you cannot redistribute the template nor its derivatives on the internet - neither
for free or commercially (e.g. selling it on template marketplace).

Thank you for understanding and respecting the license conditions.


Available Grunt commands
grunt dist (Just compile CSS and JavaScript)

Regenerates the /dist/ directory with compiled and minified CSS and JavaScript files. As a Bootstrap user, this is normally the command you want.
grunt watch (Watch)

Watches the Less source files and automatically recompiles them to CSS whenever you save a change.
grunt test (Run tests)

Runs JSHint and runs the QUnit tests headlessly in PhantomJS.
grunt docs (Build & test the docs assets)

Builds and tests CSS, JavaScript, and other assets which are used when running the documentation locally via bundle exec jekyll serve.
grunt (Build absolutely everything and run tests)

Compiles and minifies CSS and JavaScript, builds the documentation website, runs the HTML5 validator against the docs, regenerates the Customizer assets, and more. Requires Jekyll. Usually only necessary if you're hacking on Bootstrap itself.