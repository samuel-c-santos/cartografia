# 🚀 Quick Start

Use este guia rápido para começar a usar o template em 5 minutos.

## Passo 1: Copiar o Template

```bash
# Crie uma nova pasta para seu tutorial
mkdir tutorial-nome-do-seu-tutorial
cd tutorial-nome-do-seu-tutorial

# Copie todos os arquivos deste template
cp -r ../template-tutoriais/* .
```

## Passo 2: Personalizar Informações Básicas

Abra `index.html` e faça uma busca por `[PLACEHOLDER]`. Substitua os principais:

### Meta Tags (linhas 7-10)
```html
<title>Seu Título Aqui | Samuel Santos</title>
<meta name="description" content="Descrição do tutorial em ~155 caracteres">
```

### Hero Section (linha ~615)
```html
<h1>Seu Título <span class="highlight">Destaque</span> Parte Final</h1>
<p>Descrição atrativa do tutorial em 1-2 frases.</p>
```

### Article Meta (linha ~627)
```html
<span>Janeiro 2026</span>
<span>15 min de leitura</span>
<span>Python & QGIS</span>
```

## Passo 3: Adicionar Imagens

Coloque suas imagens na pasta `img/`:

```
img/
├── favicon.svg              # Ícone do site (24x24px)
├── hero-image.png           # Imagem principal (800x500px)
├── step-1.png               # Screenshot do passo 1
├── step-2.png               # Screenshot do passo 2
└── ...
```

Substitua nos placeholders:
```html
<img src="img/hero-image.png" alt="Descrição da imagem">
```

## Passo 4: Escrever o Conteúdo

### Estrutura de um Passo

```html
<div class="step-card">
    <div class="step-number">1</div>
    <h3>Título do Passo</h3>
    <p>Descrição do que será feito.</p>
    
    <!-- Screenshot -->
    <img src="img/step-1.png" alt="Descrição">
    
    <!-- Código (opcional) -->
    <div class="code-block" data-language="python">
        <code>print("Seu código aqui")</code>
    </div>
    
    <!-- Info card (opcional) -->
    <div class="info-card">
        <h4>Dica</h4>
        <p>Informação adicional.</p>
    </div>
</div>
```

### Tipos de Info Cards

**Padrão (azul)**
```html
<div class="info-card">
    <h4>Título</h4>
    <p>Conteúdo.</p>
</div>
```

**Aviso (amarelo)**
```html
<div class="info-card warning">
    <h4>Atenção</h4>
    <p>Conteúdo de alerta.</p>
</div>
```

## Passo 5: Atualizar Links

### Navbar (linhas ~570-590)
```html
<!-- Logo -->
<a href="https://seu-portfolio.com" class="logo">

<!-- GitHub -->
<a href="https://github.com/seu-usuario">

<!-- LinkedIn -->
<a href="https://linkedin.com/in/seu-perfil">
```

### Download Section (linha ~890)
```html
<a href="https://github.com/seu-usuario/seu-repo" class="download-btn">
```

### Contact Section (linhas ~920-960)
```html
<a href="mailto:seu-email@example.com">Email</a>
<a href="https://linkedin.com/in/seu-perfil">LinkedIn</a>
<a href="https://github.com/seu-usuario">GitHub</a>
<a href="https://seu-portfolio.com">Portfólio</a>
```

## Passo 6: Testar Localmente

Abra o arquivo `index.html` no navegador:

```bash
# No Windows
start index.html

# No Mac
open index.html

# No Linux
xdg-open index.html
```

## Passo 7: Publicar no GitHub

```bash
git init
git add .
git commit -m "Initial commit: Tutorial setup"
git remote add origin https://github.com/seu-usuario/seu-repo.git
git push -u origin main
```

### Habilitar GitHub Pages

1. Vá em **Settings** → **Pages**
2. Em **Source**, selecione `main` branch
3. Clique em **Save**
4. Seu tutorial estará disponível em: `https://seu-usuario.github.io/seu-repo/`

## ✅ Checklist Pré-Publicação

- [ ] Todos os `[PLACEHOLDER]` substituídos
- [ ] Imagens adicionadas e otimizadas
- [ ] Links do navbar atualizados
- [ ] Favicon presente
- [ ] Meta description < 155 caracteres
- [ ] Testado no navegador
- [ ] Testado em mobile (DevTools)
- [ ] README.md do repo atualizado

## 💡 Dicas Extras

### Otimizar Imagens

Antes de adicionar imagens, otimize-as:
- Use [TinyPNG](https://tinypng.com/) para PNG
- Use [Squoosh](https://squoosh.app/) para WebP
- Mantenha hero-image em ~200-300KB

### Estimar Tempo de Leitura

Média de leitura: **250 palavras/minuto**

```
Tempo = (Número de palavras ÷ 250) minutos
```

### Code Blocks Suportados

Use o atributo `data-language`:
- `python`
- `javascript`
- `html`
- `css`
- `bash`
- `sql`
- `json`
- `yaml`

## 📚 Recursos

- [README completo](README.md) - Documentação detalhada
- [Markdown Guide](https://www.markdownguide.org/) - Para README do repo
- [Google Fonts](https://fonts.google.com/) - Se quiser mudar a fonte

---

**Pronto!** Seu tutorial está configurado. Agora é só adicionar o conteúdo específico. 🎉
