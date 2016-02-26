# SASS-Mixins-fontSize
Calula dimanicamente a unidade relativa da fonte em "rem" com base 16px

## Como funciona?
``` javascript
SASS
div{
  @include fontSize(20px);
}

CSS
div{
  font-size:1.25rem;
}
