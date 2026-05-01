# Exercício: formulário de reserva para sessão especial de cinema

## Contexto da atividade

Você recebeu uma landing page quase pronta para divulgação de uma sessão especial de cinema.  
O site já possui identidade visual, textos promocionais, imagens e uma área reservada para a reserva de vagas.

O modelo funcional de referência está publicado em:

`https://profedvaldo.github.io/miami_vice/`

Sua tarefa será completar a parte funcional da página, construindo o formulário e aplicando validações básicas com JavaScript.

---

## Objetivo

Desenvolver um formulário de reserva integrado à landing page existente, utilizando:

- HTML
- CSS
- JavaScript

---

## O que já está pronto

A estrutura visual da landing page já foi organizada com:

- topo da página
- banner principal
- textos promocionais
- blocos de informações da sessão
- seção “Reserve sua vaga”
- espaço visual para o formulário

---

## O que deve ser feito pelo aluno

Você deverá montar o formulário dentro da área indicada no site.

### Campos obrigatórios

Crie os seguintes campos:

- Nome completo
- E-mail
- Confirmar e-mail
- Telefone
- Botão de envio

---

## Regras de validação

O formulário deve validar:

### 1. Campos vazios
Se algum campo estiver vazio, o sistema deve informar que todos os campos precisam ser preenchidos.

### 2. Confirmação de e-mail
O campo **Confirmar e-mail** deve ser igual ao campo **E-mail**.

Se os dois forem diferentes, o sistema deve exibir uma mensagem de erro.

### 3. Mensagem final
Ao final do envio:

- mostrar mensagem de erro, se houver problema
- mostrar mensagem de sucesso, se estiver tudo correto

---

## Requisitos técnicos

### HTML
- Inserir o formulário na área indicada
- Usar `input` apropriado para cada campo
- Usar `button` para envio
- Criar um espaço para exibir a mensagem ao usuário

### CSS
- Manter o padrão visual já existente
- Organizar bem os campos
- Aplicar espaçamento e alinhamento
- Destacar visualmente o formulário sem quebrar o layout da página

### JavaScript
- Selecionar os campos do formulário
- Capturar o evento de envio
- Verificar campos vazios
- Comparar os dois e-mails
- Exibir a mensagem final na tela

---

## Estrutura esperada

Exemplo de organização:

- `index.html`
- `style.css`
- `script.js`

---

## Critérios de avaliação

A atividade poderá considerar:

- montagem correta do formulário
- funcionamento das validações
- organização do código
- clareza dos nomes usados nas variáveis e elementos
- integração visual com a landing page
- mensagem de erro e sucesso funcionando corretamente

---

## Resultado esperado

Ao final, o site deverá apresentar:

- uma landing page visualmente pronta
- um formulário funcional
- validação de campos vazios
- validação dupla do e-mail
- retorno claro para o usuário

---

## Parte prática: como baixar o projeto para trabalhar localmente

Abaixo estão os passos detalhados para você pegar o projeto-base, abrir no computador, editar e depois enviar para o seu próprio repositório.

---

## Opção 1 — Baixar o projeto diretamente pelo navegador

### Passo 1 — abrir o repositório
Acesse o repositório-base informado pelo professor.

### Passo 2 — baixar os arquivos
Na página do repositório:

1. clique no botão **Code**
2. clique em **Download ZIP**
3. aguarde o download terminar

### Passo 3 — extrair o arquivo
Depois do download:

1. localize o arquivo `.zip` no computador
2. clique com o botão direito
3. escolha **Extrair aqui** ou **Extrair para...**
4. abra a pasta extraída

### Passo 4 — abrir no editor
Abra a pasta do projeto em um editor como:

- VS Code
- Cursor
- Notepad++
- outro editor de sua preferência

### Passo 5 — editar os arquivos
Trabalhe principalmente nestes arquivos:

- `index.html`
- `style.css`
- `script.js`

---

## Opção 2 — Clonar o repositório com Git

Esta opção é melhor para quem já está usando Git.

### Passo 1 — copiar a URL do repositório
Na página do repositório:

1. clique em **Code**
2. copie a URL HTTPS

### Passo 2 — abrir o terminal
Abra:

- Git Bash
- PowerShell
- Terminal do VS Code

### Passo 3 — entrar na pasta onde deseja salvar o projeto
Exemplo:

```bash
cd Documentos
```

### Passo 4 — clonar o repositório
Use o comando:

```bash
git clone URL_DO_REPOSITORIO
```

Exemplo genérico:

```bash
git clone https://github.com/usuario/repositorio.git
```

### Passo 5 — entrar na pasta clonada

```bash
cd nome-da-pasta
```

### Passo 6 — abrir o projeto no VS Code

```bash
code .
```

---

## Como executar localmente no computador

Depois de abrir a pasta do projeto:

### Opção simples
- clique duas vezes no arquivo `index.html`

### Opção recomendada
Use uma extensão como **Live Server** no VS Code:

1. abra o projeto no VS Code
2. clique com o botão direito em `index.html`
3. escolha **Open with Live Server**

Isso facilita os testes enquanto você edita.

---

## Como desenvolver a atividade

Trabalhe nesta ordem:

### Etapa 1 — observar a página pronta
Antes de escrever código, leia o site-base e entenda:

- onde ficará o formulário
- qual é o padrão visual
- quais textos já estão prontos
- onde a mensagem final deve aparecer

### Etapa 2 — montar o HTML do formulário
Crie na área indicada:

- campo nome
- campo e-mail
- campo confirmar e-mail
- campo telefone
- botão enviar
- parágrafo ou `div` para mensagem

### Etapa 3 — ajustar o CSS
Depois do HTML pronto:

- organize os campos em coluna
- aplique espaçamento
- mantenha o visual do site
- destaque o bloco do formulário

### Etapa 4 — programar o JavaScript
No arquivo `script.js`:

- selecione os campos
- capture o evento de envio
- impeça o recarregamento da página
- teste campos vazios
- compare e-mail e confirmar e-mail
- exiba a mensagem final

### Etapa 5 — testar
Faça vários testes:

- todos os campos vazios
- apenas um campo preenchido
- e-mails diferentes
- todos os campos corretos

---

## Como criar o repositório do aluno no GitHub



## Como enviar o projeto para o repositório do aluno

Existem duas formas principais.

---

## Forma 1 — Enviar pelo navegador

### Passo a passo

1. abra o repositório vazio do aluno
2. clique em **uploading an existing file** ou **Add file > Upload files**
3. arraste os arquivos da pasta do projeto
4. aguarde o upload
5. escreva uma mensagem de commit  
   Exemplo: `Entrega da atividade de formulário`
6. clique em **Commit changes**

### Atenção
Ao enviar pelo navegador:

- envie os arquivos corretos
- não envie arquivos desnecessários
- confira se `index.html` está na raiz do projeto

---

## Forma 2 — Enviar com Git

Esta é a forma mais organizada.

### Passo 1 — inicializar o Git
Se a pasta ainda não estiver com Git:

```bash
git init
```

### Passo 2 — adicionar os arquivos

```bash
git add .
```

### Passo 3 — criar o commit

```bash
git commit -m "Entrega da atividade de formulário"
```

### Passo 4 — conectar ao repositório do aluno

```bash
git branch -M main
git remote add origin URL_DO_REPOSITORIO_DO_ALUNO
```

### Passo 5 — enviar para o GitHub

```bash
git push -u origin main
```

---

## Como atualizar o repositório depois de novas mudanças

Se você continuar mexendo no projeto e quiser enviar atualização:

```bash
git add .
git commit -m "Ajustes no formulário e validações"
git push
```

---

## Como publicar no GitHub Pages

Se o professor solicitar publicação online:

1. entre no repositório do aluno
2. abra **Settings**
3. vá em **Pages**
4. em **Branch**, escolha a branch principal
5. salve
6. aguarde a geração do link

Depois disso, o site poderá ficar acessível online.

---

## Boas práticas para a entrega

Antes de enviar, confira:

- o formulário aparece corretamente
- os campos estão visíveis
- a validação de vazio funciona
- a validação do e-mail funciona
- a mensagem de sucesso aparece
- o layout não foi quebrado
- os arquivos estão organizados

---

## Dica importante

Antes de testar o sucesso, teste os erros:

- deixe campos vazios
- digite e-mails diferentes
- preencha tudo corretamente

Isso ajuda a verificar se sua validação está funcionando de verdade.

---

## Entrega

Entregar os arquivos do projeto funcionando no navegador, com:

- página completa
- formulário montado
- validações implementadas
- organização final do código

---

## Desafio extra

Se terminar antes, você pode melhorar a atividade com:

- borda vermelha em campo com erro
- borda verde em campo correto
- mensagem mais elegante
- máscara simples para telefone
- responsividade melhorada no celular
