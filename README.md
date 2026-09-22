
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

A escolha foi feita porque a página possui uma estrutura visual clara, com cabeçalho, chamada principal, formulário de e-mail, seções de conteúdo e perguntas frequentes. Isso permite reproduzir os conceitos solicitados no trabalho sem depender de interações complexas de JavaScript.

A página original apresenta uma chamada para o usuário informar o e-mail para começar, uma área de conteúdos em destaque, motivos para utilizar o serviço e perguntas frequentes.

---

## 1.1 Estrutura HTML semântica e acessível

- [x] `header`
- [x] `nav`
- [x] `main`
- [x] `section`
- [x] `article`
- [x] `footer`
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

A página foi construída observando a organização visual da página de referência, sem copiar o código-fonte original. Foram reproduzidos conceitos visuais como fundo escuro, vermelho como cor de destaque, tipografia de grande impacto, formulário de e-mail e divisão do conteúdo em blocos.

Pequenas diferenças foram feitas para adaptar a interface ao objetivo acadêmico e demonstrar conhecimentos de HTML, CSS e JavaScript.

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

O box model foi utilizado através de `padding`, `margin`, `border`, `width` e `height`. As principais cores e valores reutilizados foram definidos em `:root` através de variáveis CSS, como `--preto`, `--branco` e `--vermelho`.

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

# Organização dos arquivos

```text
trabalho_g1_frontend/
│
├── index.html
├── style.css
└── README.md
```

Os arquivos principais foram mantidos exatamente com os nomes solicitados no enunciado.

---

# Commits

O professor solicita pelo menos 8 commits distribuídos em pelo menos 3 dias diferentes.

Sugestão de histórico:

1. `cria estrutura inicial do projeto`
2. `adiciona estrutura semantica do header e hero`
3. `adiciona formulario de email`
4. `cria secao de motivos para assistir`
5. `adiciona catalogo visual de filmes`
6. `cria perguntas frequentes e rodape`
7. `adiciona responsividade mobile first`
8. `adiciona personalizacao e documentacao`

**Importante:** os commits devem ser realizados em dias diferentes durante o desenvolvimento. Não faça os oito commits de uma vez no último dia.

---

# Validação

Antes da entrega:

- Validar o HTML no https://validator.w3.org/
- Abrir a página em uma largura semelhante à de um celular
- Abrir a página em uma largura semelhante à de um desktop
- Conferir o formulário
- Tirar prints comparando a página desenvolvida com a referência
- Conferir se os três arquivos estão na raiz do repositório
- Preencher a matrícula
- Enviar o link do repositório pelo AVA

---

## Observação

Este projeto é uma reprodução acadêmica inspirada visualmente na página de referência. O código foi escrito do zero para demonstrar os conceitos solicitados na atividade.
