# Chalé dos Sonhos 🏡

Landing page para venda do **Chalé dos Sonhos** — uma casa de madeira estilo chalé no condomínio Águas da Serra Haras & Golf, Bananeiras-PB.

## 🎯 Sobre o Projeto

Site estático desenvolvido com HTML/CSS/JS puro, otimizado para SEO e conversão. Focado em apresentar o imóvel de forma atrativa e facilitar o contato com o proprietário via WhatsApp.

### Características

- ✅ Landing page responsiva (mobile-first)
- ✅ Animações CSS (fade-in on scroll, parallax)
- ✅ Otimizado para SEO (meta tags, structured data, sitemap)
- ✅ Integração WhatsApp
- ✅ Google Analytics e Facebook Pixel (placeholders)
- ✅ Lazy loading de imagens
- ✅ Performance otimizada
- ✅ Deploy automático na Vercel

## 🚀 Deploy

### Opção 1: Vercel CLI (Recomendado)

```bash
# Instalar Vercel CLI (se não tiver)
npm install -g vercel

# Fazer login
vercel login

# Deploy para produção
vercel --prod
```

### Opção 2: GitHub + Vercel Dashboard

1. Suba o projeto para o GitHub
2. Acesse [vercel.com](https://vercel.com)
3. Clique em "New Project"
4. Importe o repositório do GitHub
5. Deploy automático!

## 💻 Desenvolvimento Local

```bash
# Método 1: HTTP Server (Python)
python3 -m http.server 3000

# Método 2: HTTP Server (Node.js)
npm run dev
# ou
npx http-server . -p 3000

# Método 3: Live Server (VS Code Extension)
# Instale "Live Server" e clique com botão direito > "Open with Live Server"
```

Acesse: `http://localhost:3000`

## 📁 Estrutura do Projeto

```
chale-dos-sonhos/
├── index.html          # Landing page principal
├── favicon.svg         # Favicon do site
├── robots.txt          # Instruções para crawlers
├── sitemap.xml         # Mapa do site para SEO
├── vercel.json         # Configuração do Vercel
├── package.json        # Metadados do projeto
├── .gitignore          # Arquivos ignorados pelo Git
└── README.md           # Este arquivo
```

## 🔧 Configurações Pós-Deploy

### 1. Google Analytics

No `index.html`, substitua:
```html
gtag('config', 'G-XXXXXXXXXX');
```

Por seu ID do GA4 (ex: `G-ABC123XYZ`)

### 2. Facebook Pixel

No `index.html`, substitua:
```javascript
fbq('init', 'YOUR_PIXEL_ID');
```

Por seu Pixel ID do Facebook

### 3. Domínio Customizado

Na dashboard da Vercel:
1. Vá em **Settings** > **Domains**
2. Adicione `chaledossonhos.com.br`
3. Configure os DNS records no seu registrador:

```
Tipo A:     @ → 76.76.21.21
Tipo CNAME: www → cname.vercel-dns.com
```

## 🌐 Git & GitHub

### Inicializar Git e fazer primeiro commit

```bash
git init
git add .
git commit -m "feat: landing page Chalé dos Sonhos"
```

### Criar repositório no GitHub e subir

#### Com GitHub CLI (gh):
```bash
# Criar repo e fazer push em um comando
gh repo create chale-dos-sonhos --public --source=. --push
```

#### Sem GitHub CLI:
```bash
# 1. Crie o repo manualmente no GitHub
# 2. Adicione o remote
git remote add origin https://github.com/SEU_USUARIO/chale-dos-sonhos.git

# 3. Push
git branch -M main
git push -u origin main
```

## 📊 SEO

O site já está otimizado com:

- ✅ Meta tags (title, description, keywords)
- ✅ Open Graph (Facebook, LinkedIn)
- ✅ Twitter Cards
- ✅ Structured Data (JSON-LD) - tipo `RealEstateListing`
- ✅ Sitemap.xml
- ✅ Robots.txt
- ✅ Performance headers (Cache-Control, Security Headers)

## 📱 Contato

WhatsApp: **(83) 98120-0570**

Link direto: `https://wa.me/5583981200570?text=Olá! Tenho interesse no Chalé dos Sonhos`

## 📄 Licença

Este projeto é privado e não possui licença open source.

---

**Desenvolvido para venda do Chalé dos Sonhos | Bananeiras-PB**
