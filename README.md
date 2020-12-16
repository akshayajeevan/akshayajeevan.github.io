My Profile
---------

This is my profile where I will be updating regularly to have all the information upto-date.

The template is forked and modified from awesome [universal-resume](https://github.com/WebPraktikos/universal-resume)

Printing
---------

### Chrome

Right-click → Print.  
Also, choose the **Save as PDF** option if needed.

By expanding **More Settings**, change **Page Size** to A4 or Letter.

### Firefox

File → Print.

Choose A4 or Letter size by navigating to **Properties → Advanced → Paper Size**.

### Adobe Acrobat Reader

File → Print.

By clicking on the **Page Setup** button, you are taken to the window with A4 and Letter options.

Blocking Search Engines
---------

Disable search engine indexing by adding the following code to the `<head>`:

```html
<meta name="robots" content="noindex">
```

Language Support
---------

With [FiraGO](https://github.com/bBoxType/FiraGO) typeface, this résumé supports the following scrips: Latin, Cyrillic, Greek, Vietnamese, Arabic, Thai, Georgian, Devanagari, and Hebrew.

If you want to significantly speed up font loading time, find out what fonts you are using (under developer tools network panel) and add them to the `head` like so:

```html
<link rel="preload" href="./fonts/FiraGO-Regular.latin.woff2" as="font" crossorigin="anonymous">
```

License
---------

NonCommercial-ShareAlike 1.0 Generic (CC NC-SA 1.0)  
https://creativecommons.org/licenses/nc-sa/1.0/

### You are free to:

Share — copy and redistribute the material in any medium or format  

Adapt — remix, transform, and build upon the material

### Under the following terms:

NonCommercial — You may not use the material for commercial purposes.

ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
