## UBUNTU TIPS AND TRIK

You can use the [editor on GitHub](https://github.com/fikidedi/ubuntu/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

## PART XAMPP DI UBUNTU

### Cara Install XAMPP

Unduh file XAMPP di situs resmi https://www.apachefriends.org/download.html

File unduhan biasanya akan masuk folder Downloads.

Buka terminal (CTRL+ALT+T) dan masuk ke folder Downloads,  untuk masuk ke folder tersebut ketikkan perintah:

```markdown
$cd Downloads
$sudo ./xampp-linux-x64-7.3.5-1-installer.run
```

### Membuka manager XAMPP

```markdown
$sudo su
#cd /opt/lampp
#./manager-linux-x64.run
```

### Menajalankan dan menghentikan XAMPP 
```markdown
$sudo /opt/lampp/lampp start
$sudo /opt/lampp/lampp stop
```

### Mengubah permisi htdocs
```markdown
$sudo chmod -R 777 /opt/lampp/htdocs
```
