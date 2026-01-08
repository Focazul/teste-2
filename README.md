# Mayra Moraes - Consultoria Empresarial

Website profissional para Mayra Moraes, consultora empresarial especializada em NR1 com foco em saúde mental no trabalho.

## 🚀 Deployment / Implantação

Este site está pronto para ser publicado via GitHub Pages.

### Opção 1: GitHub Pages com Actions (Recomendado)

Este repositório já inclui um workflow do GitHub Actions que automaticamente publica o site.

**Configuração inicial:**

1. Acesse as configurações do repositório: `Settings` > `Pages`
2. Em "Build and deployment" > "Source", selecione **GitHub Actions**
3. Faça merge desta branch para `main` ou `master`
4. O workflow será executado automaticamente e o site será publicado
5. O site estará disponível em: `https://focazul.github.io/teste-2/`

**Para publicações futuras:**
- Qualquer commit na branch principal (`main` ou `master`) acionará automaticamente uma nova publicação
- Você também pode acionar manualmente via: `Actions` > `Deploy to GitHub Pages` > `Run workflow`

### Opção 2: GitHub Pages Manual

1. Acesse as configurações do repositório
2. Vá para "Pages" no menu lateral
3. Em "Source", selecione a branch principal (main/master)
4. Selecione a pasta raiz (root) como source
5. Clique em "Save"
6. O site estará disponível em: `https://focazul.github.io/teste-2/`

### Opção 3: Hospedagem Local

Para visualizar o site localmente:

```bash
# Usando Python 3
python3 -m http.server 8000

# Ou usando Python 2
python -m SimpleHTTPServer 8000

# Ou usando Node.js (npx)
npx serve .
```

Acesse: `http://localhost:8000`

## 📁 Estrutura do Projeto

```
.
├── index.html          # Página principal do site
├── assets/             # Recursos (imagens, ícones)
│   ├── favicon.svg     # Ícone do site
│   ├── header-bg.svg   # Imagem de fundo do cabeçalho
│   └── logo.svg        # Logo da Mayra Moraes
└── README.md           # Este arquivo
```

## 🎨 Características

- Design moderno e responsivo
- Otimizado para SEO
- Formulário de contato funcional
- Compatível com todos os navegadores modernos
- Suporte a temas personalizáveis

## 📝 Customização

O site inclui um SDK para personalização que permite modificar:
- Cores do tema
- Tamanhos de fonte
- Textos e títulos
- Família de fontes

## 📧 Contato

Para mais informações sobre os serviços de consultoria, entre em contato através do formulário no site.

---

© 2024 Mayra Consultoria Empresarial. Todos os direitos reservados.
