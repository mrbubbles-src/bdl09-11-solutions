```
<!-- HEADING: -->
### **Heading**
<!-- # ist quasi wie h1-6 in einer markdown file je nachdem wieviele # du vor dem text setzt. man braucht keine schließtags (</#>) -->

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6


<!-- ITALICS: -->
### **Kursiver Text**
<!-- mit (*text here*) wird der text kursiv. Alternativ mit (_text here_)  -->

*Kursiver Text bsp 1*

_Kursiver Text bsp 2_

<!-- BOLD: -->
### **Fetter Text**
<!-- Mit (**text here**) wird der text fett geschrieben. Alternativ mit (__text here__ | das sind jeweils 2x _) -->

**Fetter text bsp 1**

__Fetter text 2 bsp 2__

<!-- DURCHGESTRICHENER TEXT: -->
### **Durchgestrichener Text**
<!-- text wird mit (~~text here~~) durchgestrichen  -->

~~durchgestrichener text~~

<!-- TRENNLINIE: -->
### **Trennlinie**
<!-- wird mit (---) gemacht  -->

---

<!-- BLOCK QUOTE (ZITAT): -->

<!-- wird mit (>) geschrieben -->

> das ist ein zitat

<!-- LISTEN / UL / OL: -->
### **Listen**
<!-- UL wird mit (* text) geschrieben | OL wird mit (1. text, etc.) geschrieben. wenn man auf TAB drückt for den befehlen wird es ein nested item erstellt -->

<!-- UL: -->
#### **Unordered Lists**
* UL 1
* UL 2
* UL 3
    * nested UL 1
    * nested UL 2

<!-- OL: -->
#### **Ordered Lists**
1. OL 1
2. OL 2
3. OL 3
    1. nested OL 1
    2. nested OL 2

<!-- LINK: -->
### **Links**
<!-- in [] wird geschrieben was angezeigt wird und dahinter in () den link:  [beschreibung](link)-->

[google](www.google.com)

[stackoverflow](https://stackoverflow.com/)

<!-- IMAGE: -->
### **Bilder**
<!-- bilder werden angezeigt mit ! dann [] und dann () quasi so wie bei links nur mit einem ! am anfang: ![beschreibung](link) | Skaliert automatisch -->

![Berge](https://www.kindernetz.de/wissen/1653497600179,wie-entstehen-berge-104~_v-16x9@2dM_-ad6791ade5eb8b5c935dd377130b903c4b5781d8.jpg)


<!-- INLINE CODE: -->

<!-- mit ` TEXT ` wird code dargestellt -->

### **Inline Code**
`sudo snap install discord`

`<p> lorem ipsum </p>`

<!-- GITHUB: -->
### **Github**
<!-- ```bash dann zeilenumbruch machen und die befehle eintragen um terminal befehle aufzuschreiben dann nochmal ``` zum abschließen -->

```bash 
Terminal

touch index.html
sudo snap install discord
```

<!-- ```javascript und dann zeilenumbruch machen und die befehle eintragen um javascript befehle aufzuschreiben dann nochmal ``` zum abschließen -->

```javascript
Javascript

const name = 'Max';
function getInfo(){

}
```

<!-- ```html und dann zeilenumbruch machen und die befehle eintragen um html befehle aufzuschreiben dann nochmal ``` zum abschließen -->

```html
HTML

<div> text here </div>
```

<!-- ```python und dann zeilenumbruch machen und die befehle eintragen um python befehle aufzuschreiben dann nochmal ``` zum abschließen -->

```python
Python

def getInfo(name, address) :
    return name;
```
```
