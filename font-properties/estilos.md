# Atribuindo mais estilos ás fontes
https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant

## font-variant
* variações na apresentação fonte

https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant

```css
p {
  font-variant: small-caps;
}
```
## font-stretch
* alargamento ou encolhimento da fonte
* aceita palavras-chaves como: expandedn condensed, normal

https://developer.mozilla.org/en-US/docs/Web/CSS/font-stretch

```css
p {
  font-stretch: expanded;
}
```

## letter-spacing
* espaços entre caracteres

```css
p {
  letter-spacing: 4px;
}
```
https://developer.mozilla.org/en-US/docs/Web/CSS/letter-spacing

## word-spacing 
* Espaços entre caracteres
```css
p {
  word-spacing: 4px;
}
```
https://developer.mozilla.org/en-US/docs/Web/CSS/word-spacing

## line-height
* Espaços entre linhas
* Pode ser com unidade ou sem unidade de medida
* comuns: 1.5 ou 2

```css 
p {
  line-height: 1.6;
}
```
https://developer.mozilla.org/en-US/docs/Web/CSS/line-height

## text-transform

* Transformação do texto 

```css
p {
  text-transform: uppercase; /* capitalize | lowercase | none */
}
```
https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform

## text-decoration
* Aparencia decorativa de um texto
* line: underline | overline | line-through
    * podemos aplicar mais de 1 valor
* style: wavy | dotted | double | dashed | solid
* color: ` <color> ` values

```css
p {
  text-decoration: underline; /* shorthand */
}
```
https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration

## text-aling  
* Alinhamento de um texto

```css
p {
  text-aling: center; /* left | right | center | justify */
}
```

https://developer.mozilla.org/en-US/docs/Web/CSS/text-align

## text-shadow
* Sombras aplicada a um texto
* Permite múltiplicar valores

```css
p {
  text-shadow; 1px 1px 1px red, 2px 2px 1px green; 
  /* offset-x | offset-y | blur-radius | color  */
}
```
https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow

## shorthand
* font-style, font-variant, font-weight, font-stretch, fonte-size, line-height, e font-family. 
```css 
p {
  /*-style, -variant, -weight, -stretch, -size, -height, e -family*/
  font: italic normal bold normal 3em/1.5 Helvetica, Arial, sans-serif;
}