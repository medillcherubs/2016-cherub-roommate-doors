# 2016-cherub-roommate-doors
Interactive display for roommate feature stories. Built by Brian Meller. 



https://medillcherubs.github.io/2016-cherub-roommate-doors/

Paste this into your Wordpress post:

```
<div id="example"></div>
<script type="text/javascript" src="http://cherubs.medill.northwestern.edu/2016/wp-content/themes/cherubs2016/js/vendor/pym.min.js"></script> <script> var pymParent = new pym.Parent("example", "//medillcherubs.github.io/2016-cherub-roommate-doors/index.html", {}); </script>

<!-- Edit: https://github.com/medillcherubs/2016-cherub-roommate-doors/edit/gh-pages/index.html -->
```

Paste this into the bottom of your `index.html`:

```
<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script> <script src="https://cdnjs.cloudflare.com/ajax/libs/pym/0.4.5/pym.min.js"></script> <script> $(function(){ var pymChild = new pym.Child({polling: 500}); }); </script> 
```
