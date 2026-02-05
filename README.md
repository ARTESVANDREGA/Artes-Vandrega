# 🎨 Artes Vandrega - Website Oficial

Website institucional profissional para a Artes Vandrega, empresa especializada em comunicação visual, luminosos LED/néon e sinalética em Angola.

## 📁 Estrutura do Projeto

```
artes-vandrega-site/
├── index.html      # Página principal (estrutura HTML)
├── style.css       # Estilos CSS (design dark/neon)
├── script.js       # Funcionalidades JavaScript
└── README.md       # Este arquivo
```

## 🚀 Como Publicar no GitHub Pages

### Passo 1: Criar Repositório no GitHub

1. Acesse [github.com](https://github.com) e faça login
2. Clique no botão **"+"** (New repository)
3. Nome do repositório: `artes-vandrega` (ou outro nome)
4. Defina como **Público**
5. Clique em **"Create repository"**

### Passo 2: Fazer Upload dos Arquivos

**Opção A - Via Web (Mais fácil para iniciantes):**

1. No repositório criado, clique em **"Add file"** → **"Upload files"**
2. Arraste os 3 arquivos (`index.html`, `style.css`, `script.js`) ou clique para selecionar
3. Escreva no commit: "Primeira versão do site"
4. Clique em **"Commit changes"**

**Opção B - Via Git (Para quem tem experiência):**

```bash
# Clone o repositório
git clone https://github.com/SEU-USUARIO/artes-vandrega.git
cd artes-vandrega

# Copie os arquivos para a pasta
# (copie index.html, style.css e script.js)

# Adicione, commite e envie
git add .
git commit -m "Primeira versão do site"
git push origin main
```

### Passo 3: Ativar GitHub Pages

1. No repositório, clique em **"Settings"** (aba superior)
2. No menu lateral esquerdo, clique em **"Pages"**
3. Em **"Source"**, selecione:
   - Branch: `main` (ou `master`)
   - Pasta: `/ (root)`
4. Clique em **"Save"**

### Passo 4: Acessar o Site

- Aguarde 2-5 minutos
- O GitHub mostrará o link: `https://SEU-USUARIO.github.io/artes-vandrega/`
- **Pronto!** Seu site está no ar! 🎉

---

## ✨ Características do Site

### Design
- 🌙 Tema escuro moderno e elegante
- 💡 Detalhes em amarelo néon/dourado
- 📱 Totalmente responsivo (mobile, tablet, desktop)
- ⚡ Animações suaves e interativas

### Seções
1. **Header Fixo** - Navegação sempre visível
2. **Hero** - Apresentação impactante com efeito néon
3. **Sobre** - História e valores da empresa
4. **Serviços** - 6 cards com serviços oferecidos
5. **Portfólio** - Galeria de projetos (com lightbox)
6. **Localização** - Mapa e pontos de referência
7. **Contacto** - Formulário e informações
8. **Footer** - Links e informações adicionais

### Funcionalidades
- ✅ Menu mobile hambúrguer
- ✅ Scroll suave entre seções
- ✅ Animações ao scroll
- ✅ Formulário de contacto funcional
- ✅ Botão WhatsApp flutuante
- ✅ Voltar ao topo
- ✅ Lightbox para imagens do portfólio

---

## 🔧 Personalizações Necessárias

### 1. Informações de Contacto

No arquivo `index.html`, procure e altere:

```html
<!-- Linha ~380 - Telefone -->
<a href="tel:+244999999999">+244 999 999 999</a>

<!-- Linha ~385 - Email -->
<a href="mailto:geral@artesvandrega.com">geral@artesvandrega.com</a>

<!-- Linha ~390 - WhatsApp -->
<a href="https://wa.me/244999999999">+244 999 999 999</a>
```

### 2. Localização no Mapa

No arquivo `index.html`, linha ~420, substitua o iframe do Google Maps:

1. Acesse [Google Maps](https://maps.google.com)
2. Procure "Zango 0, Luanda, Angola"
3. Clique em **"Partilhar"** → **"Incorporar mapa"**
4. Copie o código HTML
5. Substitua o `<iframe>` no arquivo

### 3. Imagens do Portfólio

As imagens atuais são placeholders do Unsplash. Para usar fotos reais:

**Opção 1 - URLs externas:**
Substitua os `src` das imagens (linhas ~280-320) por URLs de suas fotos.

**Opção 2 - Imagens locais:**
1. Crie uma pasta `images/` no repositório
2. Faça upload das fotos
3. Altere os `src` para: `images/nome-da-foto.jpg`

### 4. Redes Sociais

No footer e seção de contacto, atualize os links das redes sociais:

```html
<!-- Linhas ~450-452 -->
<a href="LINK_FACEBOOK" title="Facebook">
<a href="LINK_INSTAGRAM" title="Instagram">
<a href="LINK_LINKEDIN" title="LinkedIn">
```

---

## 📱 Teste Responsivo

O site é totalmente responsivo. Teste em:
- 💻 Desktop (1920px, 1440px, 1024px)
- 📱 Tablet (768px)
- 📱 Mobile (480px, 320px)

Use o modo desenvolvedor do navegador (F12) para testar diferentes tamanhos.

---

## 🎨 Cores Utilizadas

| Cor | Código | Uso |
|-----|--------|-----|
| Preto | `#0a0a0a` | Fundo principal |
| Cinza escuro | `#1a1a1a` | Cards e seções |
| Amarelo/Dourado | `#FFD700` | Destaques e botões |
| Branco | `#ffffff` | Texto principal |
| Cinza médio | `#b0b0b0` | Texto secundário |

---

## ⚠️ Notas Importantes

1. **Formulário**: O formulário de contacto atual mostra uma mensagem de sucesso simulada. Para funcionar realmente, você precisa:
   - Usar um serviço como [Formspree](https://formspree.io) (gratuito)
   - Ou criar um backend em PHP/Node.js

2. **SEO**: O site já possui meta tags básicas de SEO. Recomenda-se:
   - Criar uma conta no [Google Search Console](https://search.google.com/search-console)
   - Adicionar o site para indexação

3. **Performance**: As imagens são carregadas de forma otimizada. Para melhor performance:
   - Comprima imagens antes de fazer upload
   - Use formatos WebP quando possível

---

## 📞 Suporte

Em caso de dúvidas ou problemas:
- 📧 Email: geral@artesvandrega.com
- 📱 WhatsApp: +244 999 999 999

---

**Artes Vandrega** - Iluminando marcas desde 2014 ✨
