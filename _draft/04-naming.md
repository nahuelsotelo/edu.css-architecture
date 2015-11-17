
"[...]better understand the relationship between the HTML and CSS in a given project[...]"
[_Joe Richardson_]()

"What we want is to be able to write code that is as transparent and self-documenting as possible. Transparency means that it is clear and obvious (to others) in its intent; self-documenting means that we don’t have to lose time to writing and reading lengthy, supplementary documentation."

[_Harry Roberts_](http://csswizardry.com/2015/03/more-transparent-ui-code-with-namespaces/)

### Sistemas de Nomenclaturas de clases

- SMACSS
- BEM
- SUIT
- ITCSS


### Un ejemplo: BEM (Block - Element - Modifier)

```
.nombre-del-componente__elemento--modificador {
  ...
}
```

Specificity flatness


La idea es crear un namespace para encapsular los estilos de un componente y evitar que afecten a los demás.
También se busca que las clases de un componente nos comuniquen la jerarquía del mismo.

---

&nbsp;

> "Almost all problems with CSS at scale boil down to confidence (or lack thereof): People don’t know what things do any more. People daren’t make changes because they don’t know how far reaching the effects will be. Old CSS never gets deleted because it’s hard to tell where things might be being used."

>[_Harry Roberts_](http://csswizardry.com/2015/03/more-transparent-ui-code-with-namespaces/)
