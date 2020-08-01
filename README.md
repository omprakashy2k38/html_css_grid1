# npm init
# Create a file index.html 
# Press `!` in index.html file will give some html syntax automatically in VS Code.
# Install "Live sass compiler" fROM VS CODE Extention or install golf (will compile sass and give css)

# Select main.scss and click on `Watch` option available in booton of VS Code. will crete the main.css and main.css.map file automatically.

# -------Error -------------
```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
- The resource from “http://127.0.0.1:5500/=css/main.css” was blocked due to MIME type (“text/html”) mismatch (X-Content-Type-Options: nosniff).

workaround was to simply remove the rel= attribute, i.e., change

<link rel="stylesheet" type="text/css" href="styles.css">
to

<link type="text/css" href="styles.css">

# ------------------------