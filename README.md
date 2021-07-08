Hi, I'm **NoCheat** (_@nocheatoriginal_)

---

![](https://abload.de/img/__profilbild__s2j47.jpeg "Hi!")

---
- Suluzel Studios (Developer Team)

---
# Programing languages: 
  1.  C#
  2.  Java 
  3.  Python


```python
import markdown

def to_html(textfile):
    with open(textfile + '.md', 'r') as file:
        text = file.read()
        html = markdown.markdown(text)
    with open(textfile + '.html', 'w') as file:
        file.write(html)

to_html("README")
```

---
