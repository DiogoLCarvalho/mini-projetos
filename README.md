## :star2: Mini Projetos :star2:
 

<p align='justify'>

 Este repositório tem o objetivo de agrupar em um só lugar todos os mini projetos que já desenvolvi. Contendo estilos em textos, galerias, efeitos, etc. 
 
</p>

### Projetos
* [Menu Trigger](#id01)
* [Modo Escuro](#id02)

## <i> Menu Trigger <a name="id01"></a> </i> <img src="https://img.icons8.com/color/48/000000/html-5--v1.png" width='30px' align="center"> <img src="https://img.icons8.com/color/48/000000/css3.png" width='30px' align="center">

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

<!-- ============================================================= NOVO PROJETO ================================================================ -->

## <i> Modo Escuro <a name="id02"></a> </i> <img src="https://img.icons8.com/color/48/000000/javascript--v1.png"  width='30px' align="center" /> <img src="https://img.icons8.com/color/48/000000/html-5--v1.png" width='30px' align="center"> <img src="https://img.icons8.com/color/48/000000/css3.png" width='30px' align="center">

<p align="center">
   <img src="https://user-images.githubusercontent.com/84794798/152168683-c1a7600d-fd93-4ac4-9e76-e70ea93df37e.png" alt="" width="60%" >
</p>

<h4 align='right'>

[Código completo](https://github.com/DiogoLCarvalho/mini-projetos/tree/main/codigos/pj002) 
 
</h4>

### Explicação Geral

<p  'align= justify'>
 
Para aplicar o modo escuro é preciso usar as variáveis CSS. Todas as cores que precisam ser modificadas devem ter um valor em uma variável. O funcionamento é com <i>JavaScript</i>. Ao clicar no <i>input </i> as cores das variáveis vão ser modificadas, pois uma classe no <i>root </i> vai ser aplicada. 

</p>

```js
const html = document.querySelector('html');
const checkbox = document.querySelector('#trocar');

checkbox.addEventListener('click',function () {
    html.classList.toggle('dark-mode');
})
```

#### Detalhes a mencionar :exclamation:

<p  'align= justify'>
 
A classe aplicada no <i>JavaScript</i> precisa ser a mesma no CSS. 

</p>
