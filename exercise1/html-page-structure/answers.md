# HTML page structure: my answers

## 1. What is the job of the `head`?
`<head>` does not display content on the page, but stores the information of the page, some examples changing the browser tab:<br>
`<link rel="icon" href="images/favicon.png">` display the icon in browser tab
`<title>Jason's profile</title>` display the title in browser tab

## 2. What is the job of the `body`?
`<body>` will display content on the page

## 3. Why does `<title>` change the browser tab, and not the visible page?
because `<title>` is placed inside `<head>` which stores the information of the page, it does not display content on the page; only `<body>` will change the visible page

## 4. When must you use `<ol>`, and not `<ul>`?
`<ul>` is unordered/bullet list of items, `<ol>` is ordered/numbered list of items, important for step-by-step purposes

## 5. Why must an image have useful alt text?
easier to find/search in the codes for editors, and if the image couldn't load, the text from alt= will appear instead of image, and help those using screen reader because they can't see

## 6. What connects a `<label>` to an `<input>`?
if there is `<label for="person_name">Person Name</label>` and `<input id="person_name" type="text" placeholder="John">`<br>
If i click the "Person Name", it will focus the search box, allow me to input keyboard