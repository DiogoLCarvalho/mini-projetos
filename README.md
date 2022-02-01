## :star2: Mini Projetos :star2:
 

<p align='justify'>

 Este repositório tem o objetivo de agrupar em um só lugar todos os mini projetos que já desenvolvi. Contendo estilos em textos, galerias, efeitos, etc. 
 
</p>

### Projetos
* [Menu Trigger](#id01)

## <i> Menu Trigger <a name="id01"></a> </i>

<p align="center">
   <img src="https://user-images.githubusercontent.com/84794798/151982515-913ab4ac-8773-47b5-ae44-b18f616a209e.jpg" alt="" width="60%" >
</p>

<h4 align='right'>

[Código completo](https://github.com/DiogoLCarvalho/mini-projetos/tree/main/codigos/pj001) 
 
</h4>

### Explicação Geral

<p  'align= justify'>
 
A ideia é apenas usar CSS. Utilizando a interação entre <i>input</i> e <i>label</i> do HTML. O <i>input</i> ficará invisível dentro de uma <i>div</i>. Ele precisará ter um <i>id</i> idêntico ao <i>for</i> da <i>label</i> para criar a interação. Ao clicar no <i>label</i> o <i>input</i> é acionado. Com isso o CSS faz o resto do trabalho <img src="https://c.tenor.com/Iv28avwJBSgAAAAj/oh-yeah-pikachu.gif" width="50px"  align="center">

</p>

```css
.nomeDaClasse-input:checked + .nomeDaClasse-div .text-div{
    display: block;
}
   
.nomeDaClasse-input:checked + .nomeDaClasse-div .icone-div::after{
    transform: rotate(45deg) scale(1.08);
}
```

#### Detalhes a mencionar :exclamation:

<p  'align= justify'>
 
O que você quer que apareça precisa ter um <i>display:none</i> no CSS. No meu projeto o texto <i>lorem</i> está invisível, apenas aparecendo ao clicar no <i>label</i>. 

</p>
