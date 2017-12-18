Experiments With GitHub's Rendering of Links
============================================
Code:

    <foo>

Output:

<foo>

---

Code:

    <foo/>

Output:

<foo/>

---


Code:

    <foo/bar.md>

Output:

<foo/bar.md>

---

Code:

    [foo](foo)

Output:

[foo](foo)

---

Code:

    [foo/](foo/)

Output:

[foo/](foo/)

---

Code:

    [foo/bar.md](foo/bar.md)

Output:

[foo/bar.md](foo/bar.md)

---

Code:

    <./foo>

Output:

<./foo>

---

Code:

    <./foo/>

Output:

<./foo/>

---

Code:

    <./foo/bar.md>

Output:

<./foo/bar.md>

---

Code:

    <https://www.example.com/>

Output:

<https://www.example.com/>
