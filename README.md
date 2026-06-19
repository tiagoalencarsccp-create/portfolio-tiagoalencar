# Atividade Prática — Introdução ao Git e GitHub

## Objetivo

Nesta atividade você irá praticar os comandos básicos do Git e o fluxo de trabalho utilizando GitHub.

Ao final da atividade você terá:

- Criado um repositório a partir de um template.
- Clonado o repositório para sua máquina.
- Editado arquivos do projeto.
- Criado commits.
- Enviado suas alterações para o GitHub.

---

# Parte 1 — Criar seu repositório

## Passo 1: Criar um repositório usando o template

1. Acesse o repositório disponibilizado na aula.
2. Clique no botão **Use this template**.
3. Selecione **Create a new repository**.
4. Escolha um nome para seu repositório.

Sugestão:

```text
portfolio-seunome
```

Exemplos:

```text
portfolio-maria
portfolio-joao
portfolio-ana
```

5. Deixe o repositório como **Public**.
6. Clique em **Create repository**.

Agora você possui uma cópia própria do projeto.

---

# Parte 2 — Clonar o repositório

## Passo 2: Copiar a URL

Dentro do seu repositório:

1. Clique no botão verde **Code**.
2. Copie a URL HTTPS.

Exemplo:

```text
https://github.com/seu-usuario/portfolio-seunome.git
```

---

## Passo 3: Clonar o projeto

Abra o terminal ou o VS Code e execute:

```bash
git clone URL_DO_REPOSITORIO
```

Exemplo:

```bash
git clone https://github.com/maria/portfolio-maria.git
```

Entre na pasta criada:

```bash
cd portfolio-maria
```

Abra o projeto no VS Code:

```bash
code .
```

---

# Parte 3 — Personalizar o portfólio

Abra o arquivo:

```text
index.html
```

Procure todos os locais marcados com:

```html
<!-- EDITAR -->
```

Substitua os textos pelos seus próprios dados.

---

## Informações obrigatórias

### Profissão

Troque:

```html
<p class="tag">Desenvolvedor Web</p>
```

Por algo relacionado ao seu perfil.

Exemplos:

```html
<p class="tag">Estudante de Tecnologia</p>
```

ou

```html
<p class="tag">Desenvolvedor Front-End</p>
```

---

### Nome

Troque:

```html
<h1>Olá, eu sou <span>Seu Nome</span></h1>
```

Por:

```html
<h1>Olá, eu sou <span>Maria Silva</span></h1>
```

---

### Apresentação

Troque:

```html
Escreva aqui uma breve apresentação sobre você.
```

Por um pequeno texto.

Exemplo:

```html
Sou estudante da área de tecnologia e estou aprendendo programação, Git e
desenvolvimento web.
```

---

### Foto

Troque:

```html
<img src="https://via.placeholder.com/350" alt="Foto de Perfil">
```

Você possui duas opções:

#### Opção 1 — Utilizar uma imagem da internet

Substitua a URL por uma imagem pública.

Exemplo:

```html
<img src="https://site.com/minha-foto.jpg" alt="Foto de Perfil">
```

#### Opção 2 — Utilizar uma imagem salva no projeto (recomendado)

1. Crie uma pasta chamada:

```text
images
```

2. Adicione uma foto dentro dessa pasta.

Exemplo:

```text
images/
└── foto.jpg
```

3. Atualize o atributo `src` da imagem:

```html
<img src="images/foto.jpg" alt="Foto de Perfil">
```

Você pode utilizar uma foto sua, uma imagem de avatar ou qualquer imagem apropriada para representar seu perfil.


### Sobre Mim

Substitua o texto por uma breve descrição sobre você.

Exemplo:

```html
Atualmente estudo programação e tenho interesse em desenvolvimento web e análise
de dados.
```

---

### Projetos

Substitua as descrições dos três projetos.

Você pode utilizar:

- Trabalhos da faculdade.
- Projetos pessoais.
- Exercícios desenvolvidos em aula.

Exemplo:

```html
<p>Calculadora desenvolvida utilizando HTML, CSS e JavaScript.</p>
```

---

### Contato

Substitua:

```html
Email: seuemail@email.com
```

e

```html
Instagram: @seuinstagram
```

pelos seus dados.

---

### Rodapé

Troque:

```html
© 2026 - Seu Nome
```

pelo seu nome.

---

# Parte 4 — Salvar as alterações no Git

Após finalizar as edições, abra o terminal.

Verifique os arquivos modificados:

```bash
git status
```

---

## Adicionar os arquivos

```bash
git add . ou git add index.html
```

Você pode enviar todas as alterações de uma vez, mas o ideal é que siga as boas práticas de commits atômicos.
---

## Criar um commit

```bash
git commit -m "feat: Adicionar biografia"
git commit -m "feat: Adicionar informações de contato"
```

Você pode utilizar outra mensagem de commit se desejar.

---

# Parte 5 — Enviar para o GitHub

Envie as alterações para seu repositório:

```bash
git push
```

Caso seja o primeiro envio e o Git solicite autenticação, realize o login na sua conta GitHub.

Após o push:

1. Abra seu repositório no GitHub.
2. Atualize a página.
3. Confirme se suas alterações foram enviadas com sucesso.

---

# Entrega

Envie ao professor:

- Link do seu repositório GitHub.

---

# Checklist

Antes de entregar, confirme:

- [ ] Criei um repositório usando o template.
- [ ] Clonei o repositório.
- [ ] Editei todos os campos marcados com <!-- EDITAR -->.
- [ ] Fiz pelo menos um commit.
- [ ] Enviei as alterações para o GitHub com git push.
- [ ] Confirmei que as alterações aparecem no GitHub.
