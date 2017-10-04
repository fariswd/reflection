# reflection

## Tag HTML

- HTML (Hyper Text Markup Language): Kerangka dasar website
```html
<!DOCTYPE HTML>
<html>
...
</html>
```
- Section <head>: meta, style, css, title
- Section <body>: navbar, content, footer
- Heading dibagi 6, mulai dari yang terbesar(1) sampai terkecil(6) 
```html
<h1>, <h2>, ... , <h6> 
```
- List ul jika unlisted(point), ol jika onlisted(number)
```html
<ul>
 <li> ... <li>
 <li> ... <li>
</ul>
```
- Hyperlink <a>
```html
<a href="..." />
```
- Image <img>
```html
<img src="..." />
```
- Comment 
```html
<!-- ...coment... -->
```  


## Tag CSS

- CSS (Cascading Style Sheet): Mempercantik tampilan website
- Ditempatkan di bawah section <head> pada <html>
```html
<link href="..." type="text/css" rel="stylesheet">
```
- Pointer . untuk class, # untuk id
- Struktur CSS
```css
h1 {
 font-size: 42px;
}
```
- Comment 
```css 
/* ...coment... */
```
- Contoh Pointer untuk h1 pada class id
```css 
.id h1 {
 color: red;
}
```  


## CLI COMMAND

- Navigasi cd
- New Folder mkdir
- Hapus File rm
- Directory lookup ls
- Position pwd
- Move mv
- Copy cv  


## GIT

- Git/ version controller
- Status git status
- Initialize git init
- Add file git add . 
- Add commit git -m "first commit"
- Push 1st time git remote origin "git ssh address"
- Push git push -u origin master
- New branch git checkout -b "development"
- Switch branch git checkout master

