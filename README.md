Mayra Moraes — Landing page

Site estático para divulgação de serviços de consultoria empresarial.

## 🚀 Deploy no Vercel

### Opção 1: Interface Web (Recomendado)
1. Acesse [vercel.com](https://vercel.com)
2. Faça login com GitHub
3. Clique em "Add New Project"
4. Importe este repositório
5. Clique em "Deploy" (configuração automática)

### Opção 2: CLI
```bash
# Instalar Vercel CLI
npm i -g vercel

# Deploy
vercel

# Deploy em produção
vercel --prod
```

### Opção 3: GitHub (Push e Deploy Automático)
1. Crie um repositório no GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   gh repo create mayra-consultoria --public --source=. --remote=origin --push
   ```
2. Conecte o repositório no Vercel (opção 1)
3. Cada push no `main` fará deploy automático

## ✅ Checklist Pré-Deploy
- [x] Todas as referências de assets existem
- [x] Scripts SDK removidos (não funcionam em deploy estático)
- [x] CSS sem erros de sintaxe
- [x] Logo.jpg presente na raiz
- [x] vercel.json configurado
- [x] .gitignore atualizado

## 📁 Estrutura
```
├── index.html      # Página principal
├── logo.jpg        # Logo da empresa
├── vercel.json     # Configuração Vercel
└── README.md       # Este arquivo
```

## 🔧 Customização
Edite o conteúdo diretamente no `index.html`:
- Títulos e textos: procure por `id="hero-title"`, `id="services-title"`, etc.
- Cores: altere as variáveis CSS em `:root`
- Serviços: modifique os `.service-card`

## 📞 Formulário de Contato
O formulário atualmente apenas exibe mensagem de sucesso. Para funcionar:
- Integre com [Formspree](https://formspree.io)
- Use [Vercel Forms](https://vercel.com/guides/deploying-react-forms-using-formspree-with-vercel)
- Ou adicione um backend serverless
