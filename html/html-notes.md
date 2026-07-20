# HTML (HyperText Markup Language)
- <tagname> content </tagname>
- file extension (.html)

## Comment
- <!--Comment goes-->

## HTML Tag
- h1 to h6 ==> to write title
- <p>===> paragraph
- <b> ==> bold text
- <strong> ==> bold with important
- <i> => only italic
- <em> => itlic with important

## List
- Order list(ol) => 1, A, a, i, I
- unorder list(ul) => (type=> disc, circle, square)
- description list(dl) => (dl, dt, dd)
## Link (achor <a>)
- <a>, attribute=> href, target
- For example => <a href="https://google.com">Google</a>
## table
- data display in rows and column format
- <table>
- <tr> => table row
- <th> =>
- <td>
- <thead>
- <tbody>
- <tfoot>
-  attribute=> rowspan, colspan
- <caption>
## Form
- <form>
- text, number, email, password, radio, checkbox, color, date, url, week, month, file,... etc.
- <select> <option>, etc.

## Inline element and Block level element
- inline element => <a>, <img>, <span>, <strong>, <b>, <em> ,etc.
- block => <div>, <form>, <section>, <p>, <h1>,,,etc.

## Meta tag 

## Semantic tag
- <header>, <nav>, <main>, <section>, <aside>, <article>, <footer>, <summary>, <details>, etc.


# Git and Github
- Open terminal (for windows git bas)
- ssh-keygen (press enter enter enter....)
- For windows => go to .ssh directory => type id_33343A.pub
- for mac=> cd .ssh=> ls=> cat id_33343A.pub
- for linux=> cd .ssh=> ls=> cat id_33343A.pub

- copy that ssh public key and add to github account.

# git command
- git clone git@github.com:nareshtharu-dev/frontend-2.git

## Set user name and email
- git config --global user.name "Your name"
- git config --global user.email "Your email"
- git config --list


echo "# frontend-2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:nareshtharu-dev/frontend-2.git
git push -u origin main





