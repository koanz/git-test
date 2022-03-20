# Cabeceras
# Cabecera h1
## Cabecera h2
### Cabecera h3
#### Cabecera h4
##### Cabecera h5
###### Cabecera h6<br><br>
# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- formato *italica* primer forma.
- formato _italica_ segunda forma.
- formato **bold o strong** primer forma.
- formato __bold o strong__ segunda forma.
- formato ~~tachado~~.
- combinando formatos, como: *italica*, **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="http://www.google.com">Esto es un link HTML (generado en tag html: a)</a>
- [Esto es un link HTML](http://www.google.com)

# Imagenes
![Logo Markdown](https://geekytheory.com/content/images/size/w2000/2014/03/markdown.png)

# Code Snippets
Código en Java
```Java
/**
 * @author John Smith <john.smith@example.com>
*/
package l2f.gameserver.model;

public abstract strictfp class L2Char extends L2Object {
  public static final Short ERROR = 0x0001;

  public void moveTo(int x, int y, int z) {
    _ai = null;
    log("Should not be called");
    if (1 > 5) { // wtf!?
      return;
    }
  }
}
```
Código en Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```