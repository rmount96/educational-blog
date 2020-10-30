# Full HTML Document

# Must have these elements to be a valid document

```html
    <!DOCTYPE html>
    <html>
        <head>
            <title></title>
        </head>
        <body>
        Content of the body of doc goes here
        </body>
    </html>
```
## Optionally, you can use the '!' command in your html file in VSCode and press enter to automatically form a valid document.

```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
We can immediately see some changes from the first to the second layout:
1. html adds preferred language to be interpretted
```html
<html lang="en">
```
2. Meta charset is added, UTF-8 is the only valid encoding for HTML5 docs, so is added by default
```html
<meta charset="UTF-8">
```
3. The name viewport is also added by default with the content specified to be available to mobile devices
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
4. Finally a title is added "Document", this will need to be changed as the user will see the title in the toolbar of their web-browser

>There are various names with content that can and should be added that can be found at https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta