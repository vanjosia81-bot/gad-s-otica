# GAD'S Ótica — PWA 🕶️

> Aplicativo Progressive Web App completo para a **GAD'S Ótica**, localizada na Galeria Araçá, Imbiribeira, Recife-PE.

[![Deploy to GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-gold?style=for-the-badge&logo=github)](https://pages.github.com)
![PWA](https://img.shields.io/badge/PWA-Instalável-orange?style=for-the-badge)
![MediaPipe](https://img.shields.io/badge/AR-MediaPipe-green?style=for-the-badge)

---

## 📱 Demonstração

Após publicar no GitHub Pages, o app ficará disponível em:
```
https://SEU-USUARIO.github.io/gads-otica/
```

---

## 🗂️ Estrutura

```
gads-otica/
├── index.html        → App principal (PWA)
├── medidas.html      → Tomador de Medidas AR (MediaPipe)
├── admin.html        → Painel de Administração
├── manifest.json     → Configuração PWA instalável
├── sw.js             → Service Worker (modo offline)
├── icon.svg          → Ícone da loja
└── favicon.svg       → Favicon
```

---

## ✅ Funcionalidades

### App do Cliente (`index.html`)
- 🕶️ Catálogo com busca e filtros por categoria
- 🤳 Prova Virtual AR com câmera frontal (5 modelos de óculos)
- 🛒 Carrinho de compras com persistência
- 💳 Pagamento via Pix, Cartão ou WhatsApp
- 📋 Upload de receita médica (PDF/foto)
- 👤 Cadastro e login de cliente
- 🏆 Programa de Fidelidade GAD'S Club
- 🕐 Horário de funcionamento em tempo real
- 📍 Link direto para Google Maps e WhatsApp
- 📲 Instalável como app nativo (PWA)
- 🔌 Funciona offline (Service Worker)

### Tomador de Medidas (`medidas.html`)
- 📐 Captura com câmera usando MediaPipe Face Mesh (468 landmarks)
- Mede: DNP bilateral, Altura de Montagem, Diâmetro Mínimo, Ângulo Pantoscópico, DCV
- Análise de formato do rosto + recomendações de armação
- Laudo completo exportável por WhatsApp
- Entrada manual como fallback

### Painel Admin (`admin.html`)
- 📊 Dashboard com KPIs e gráficos
- 🗃️ CRUD completo de produtos
- 📦 Gestão de pedidos (Pendente → Pago → Enviado)
- 📋 Visualização de receitas médicas recebidas
- 📐 Tabela de medidas ópticas capturadas
- 👥 Gestão de clientes com pontos fidelidade
- 🎯 Cupons e promoções
- ⚙️ Configurações da loja
- ⬇️ Export de backup em JSON

---

## 🚀 Publicar no GitHub Pages

### Passo a passo:

1. **Criar repositório** no GitHub chamado `gads-otica`

2. **Fazer upload dos arquivos** (via interface web ou Git):
   ```bash
   git init
   git add .
   git commit -m "feat: GAD'S Ótica PWA v1.0"
   git remote add origin https://github.com/SEU-USUARIO/gads-otica.git
   git push -u origin main
   ```

3. **Ativar GitHub Pages:**
   - Vá em **Settings → Pages**
   - Source: `Deploy from a branch`
   - Branch: `main` → pasta: `/ (root)`
   - Clique **Save**

4. **Acesse em ~2 minutos:**
   ```
   https://SEU-USUARIO.github.io/gads-otica/
   ```

### ⚡ Publicar em 1 clique (alternativa):
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/SEU-USUARIO/gads-otica)

---

## 📞 Dados da Loja

| Campo | Dado |
|---|---|
| **Nome** | GAD'S Ótica |
| **Endereço** | Rua Arq. Luiz Nunes, 873 – Galeria Araçá, Imbiribeira, Recife-PE |
| **CEP** | 51170-445 |
| **WhatsApp** | (81) 99782-1384 |
| **Instagram** | [@oticagads](https://instagram.com/oticagads) |
| **Horário** | Seg–Sex 9h–17h30 · Sáb 9h–12h · Dom Fechado |

---

## 🎨 Identidade Visual

| Variável | Valor | Uso |
|---|---|---|
| `--au` | `#c9922a` | Dourado principal |
| `--aum` | `#e5a83a` | Dourado médio |
| `--aul` | `#f5c95e` | Dourado claro |
| `--bg` | `#0e0b05` | Fundo escuro |
| `--tx` | `#f5ead8` | Texto principal |

---

## 📦 Tecnologias

- **HTML5 + CSS3 + Vanilla JS** — Zero dependências de framework
- **MediaPipe Face Mesh** — Detecção facial AR (via CDN)
- **Google Fonts** — Cormorant Garamond + DM Sans + JetBrains Mono
- **PWA** — manifest.json + Service Worker
- **localStorage** — Persistência de dados (sem backend)

---

## 📝 Licença

Desenvolvido exclusivamente para GAD'S Ótica Araçá, Recife-PE.  
© 2026 GAD'S Ótica — Todos os direitos reservados.
