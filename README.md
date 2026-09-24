
**Alunos:** Ana Luisa, Mateus Vicente
**Matrícula:** 1139662, 1140004
**Disciplina:** Front-End  
**Professor:** Matheus Henrique Barquette  
**Período:** G1  
**Referência:** Netflix Brasil  
**Link da referência:** https://www.netflix.com/br/

---

## 1. Referência escolhida

A referência escolhida foi a página inicial da Netflix Brasil.

A escolha foi feita porque a página possui cabeçalho, chamada principal, formulário de e-mail, seções de conteúdo e perguntas frequentes. 

A página original apresenta uma chamada para o usuário informar o e-mail para começar, uma área de conteúdos em destaque, motivos para utilizar o serviço e perguntas frequentes.

---

## 1.1 Estrutura HTML semântica e acessível

- [x] `header`: Cabeçalho
- [x] `nav` : Liks de  navegação 
- [x] `main` : Conteudo da página 
- [x] `section` : Divide o conteúdo em partes  
- [x] `article` : Contúdo individual dentro da uma seção 
- [x] `footer` : Rodapé
- [x] Formulário com `label` associado ao campo
- [x] Campo de e-mail com `type="email"`
- [x] Navegação com `aria-label`
- [x] Mensagem do formulário com `aria-live`

### Justificativa

A estrutura foi dividida em elementos semânticos para representar as diferentes partes da página. O `header` contém a identidade visual e a navegação; o `main` concentra o conteúdo principal; as `section` separam os blocos de conteúdo; os `article` representam cartões independentes; e o `footer` contém informações finais.

O formulário possui uma `label` associada ao campo de e-mail através dos atributos `for` e `id`. Também foi utilizado `type="email"` para permitir uma validação básica do navegador.

---

## 1.2 Fidelidade visual

- [x] Cabeçalho inspirado na referência
- [x] Fundo escuro
- [x] Destaque em vermelho
- [x] Chamada principal em destaque
- [x] Formulário de e-mail
- [x] Seções separadas por faixas escuras
- [x] Cartões de conteúdo
- [x] Área de perguntas frequentes

### Justificativa

A página foi construída observando a organização visual da página de referência, sem copiar o código-fonte original. Foram reproduzidos conceitos visuais como fundo escuro, vermelho como cor de destaque, tipografia de grande impacto, formulário de e-mail e divisão do conteúdo em blocos.Pequenas diferenças foram feitas.
---

## 1.3 CSS: seletores, box model e variáveis

- [x] Seletores por classe
- [x] Seletores de descendentes
- [x] Pseudo-classes como `:hover`, `:focus` e `:open`
- [x] Box model
- [x] Variáveis CSS
- [x] Unidades relativas e absolutas

### Justificativa

Foram utilizadas classes para organizar os componentes, seletores descendentes para estilizar elementos dentro de determinados componentes e pseudo-classes para estados de interação.

O box model foi utilizado através de `padding`(espaço dentreo do elemento), `margin`(espaço forado elemento), `border`(borda do elemento), `width`(largura) e `height`(altura). As principais cores e valores reutilizados foram definidos em `:root` através de variáveis CSS, como `--preto`, `--branco`, `--vermelho` e `--azul`.

---

## 1.4 Responsividade: Flexbox, Grid e mobile first

- [x] CSS desenvolvido primeiro para telas menores
- [x] Flexbox
- [x] CSS Grid
- [x] Media query com `min-width`
- [x] Layout para celular
- [x] Layout para desktop

### Justificativa

A versão padrão do CSS foi criada pensando primeiro em telas pequenas. O layout começa com elementos empilhados e grades menores.

A partir de `@media (min-width: 768px)`, os elementos são reorganizados para aproveitar melhor telas maiores. O projeto utiliza Flexbox no cabeçalho, formulário e rodapé, além de CSS Grid nos cartões e na área de filmes.

---

## 1.5 Personalização e originalidade

- [x] Seção "Sobre este clone"
- [x] Identificação acadêmica no rodapé
- [x] Área de personalização própria

### Justificativa

Foi criada uma seção chamada "Sobre este clone", que não faz parte da referência original. Ela explica que a página foi construída para o trabalho G1 e demonstra uma personalização feita pelo aluno.

---

# JavaScript

Foi utilizado JavaScript básico no formulário.
Quando o usuário envia um e-mail inválido, uma mensagem de erro é exibida. Quando o e-mail é válido, o formulário apresenta uma mensagem informando que o cadastro foi recebido. Como este é um projeto acadêmico, não existe conexão com um sistema real de cadastro.

---

## Observação

Este projeto é uma reprodução acadêmica inspirada visualmente na página de referência. O código foi escrito do zero para demonstrar os conceitos solicitados na atividade.
