# Skynet — Monitor de IA

Dashboard de monitoramento de percepção de marcas em assistentes de IA (ChatGPT).

## Como publicar no GitHub Pages

### Passo 1 — Criar conta no GitHub
1. Acesse [github.com](https://github.com) e clique em **Sign up**
2. Crie uma conta gratuita (só precisa de email)

---

### Passo 2 — Criar o repositório
1. Clique no **+** no canto superior direito → **New repository**
2. Preencha:
   - **Repository name**: `skynet-monitor` (ou qualquer nome)
   - **Visibility**: **Private** (recomendado — seus dados ficam protegidos)
   - Marque **Add a README file**
3. Clique em **Create repository**

---

### Passo 3 — Fazer upload dos arquivos
1. Dentro do repositório, clique em **Add file → Upload files**
2. Arraste todos os arquivos desta pasta:
   - `index.html`
   - `marca-1.html`
   - `marca-2.html`
   - `marca-3.html`
3. No campo **Commit changes**, escreva: `Subindo dashboards`
4. Clique em **Commit changes**

---

### Passo 4 — Ativar o GitHub Pages
1. No repositório, clique em **Settings** (aba no topo)
2. No menu lateral, clique em **Pages**
3. Em **Source**, selecione:
   - Branch: **main**
   - Pasta: **/ (root)**
4. Clique em **Save**
5. Aguarde 1-2 minutos
6. A URL aparecerá na mesma tela, no formato:
   ```
   https://SEU-USUARIO.github.io/skynet-monitor/
   ```

---

### Passo 5 — Acessar no tablet
Abra o Chrome ou Samsung Internet no Galaxy Tab S10 FE e acesse a URL acima.

**Dica:** Para adicionar à tela inicial como app:
- Chrome: menu ⋮ → **Adicionar à tela inicial**
- Samsung Internet: menu ☰ → **Adicionar página a** → **Tela inicial**

---

## Estrutura dos arquivos

```
skynet-monitor/
├── index.html      ← Página inicial (escolha de marca)
├── marca-1.html    ← Dashboard Marca 1 (acento azul)
├── marca-2.html    ← Dashboard Marca 2 (acento verde)
└── marca-3.html    ← Dashboard Marca 3 (acento âmbar)
```

## Observações importantes

- **Chave de API**: precisa ser digitada uma vez em cada dispositivo/browser que acessar
- **Dados locais**: o histórico e configurações ficam salvos no browser de cada dispositivo (localStorage) — não são sincronizados entre dispositivos
- **Privacidade**: o repositório privado significa que só você vê os arquivos no GitHub, mas a URL do Pages é pública — não compartilhe com quem não deve ter acesso

## Atualizando os dashboards

Quando receber versões novas dos arquivos `.html`:
1. No GitHub, abra o repositório
2. Clique no arquivo a substituir → ícone de lápis (editar) ou arraste diretamente
3. Ou use **Add file → Upload files** e selecione os novos arquivos (o GitHub substitui automaticamente)

---

*Skynet Monitor — Powered by Claude AI (Anthropic)*
