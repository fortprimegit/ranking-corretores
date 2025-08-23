# Sistema Ranking Corretores - FORTPRIME

Sistema web completo para gerenciamento e visualização de ranking de corretores de imóveis.

## 🚀 Deploy Gratuito no GitHub Pages

Para publicar este site gratuitamente no GitHub Pages, siga estes passos:

### 1. Criar conta no GitHub
- Acesse [github.com](https://github.com) e crie uma conta gratuita (se ainda não tiver)

### 2. Criar novo repositório
- Clique em "New repository"
- Nome do repositório: `ranking-corretores` (ou outro nome de sua escolha)
- Marque como "Public"
- Clique em "Create repository"

### 3. Fazer upload do arquivo
- No repositório criado, clique em "uploading an existing file"
- Faça upload do arquivo `index.html`
- Adicione uma mensagem de commit: "Initial commit: Sistema Ranking Corretores"
- Clique em "Commit changes"

### 4. Ativar GitHub Pages
- Vá para "Settings" do repositório
- Role para baixo até a seção "Pages"
- Em "Source", selecione "Deploy from a branch"
- Em "Branch", selecione "main" (ou "master")
- Clique em "Save"

### 5. Acessar o site
- Aguarde alguns minutos
- Seu site estará disponível em: `https://SEU_USUARIO.github.io/ranking-corretores`

## 📊 Integração com Google Sheets

Este site agora puxa os dados diretamente de uma planilha do Google Sheets. Para que isso funcione corretamente, sua planilha deve estar **publicada na web como CSV**.

**Como garantir que sua planilha esteja configurada corretamente:**

1.  Abra sua planilha no Google Sheets.
2.  Vá em `Arquivo > Compartilhar > Publicar na web`.
3.  Na janela que abrir, selecione a aba (planilha) que contém os dados do ranking.
4.  Escolha o formato `Valores separados por vírgulas (.csv)`.
5.  O link gerado por essa opção já foi inserido no código do `index.html`.

**Estrutura da Planilha:**

Certifique-se de que as colunas da sua planilha CSV tenham os seguintes cabeçalhos (exatamente como escrito, respeitando maiúsculas/minúsculas):

- `CORRETOR` (Nome do corretor)
- `V.Líq` (Vendas Líquidas)
- `VENDAS` (Número de Vendas)
- `PROPOSTAS` (Número de Propostas)
- `VISITAS` (Número de Visitas)
- `AGENDAMENTOS` (Número de Agendamentos)
- `DISTRATOS` (Número de Distratos)

## 📱 Funcionalidades

✅ **Sistema de Login** (removido para integração com Google Sheets, o site agora é público)
✅ **Gerenciamento de Corretores** (removido, os dados são gerenciados no Google Sheets)
✅ **Ranking Automático** - ordenação por vendas líquidas com zonas coloridas
✅ **Análises e Gráficos** - estatísticas detalhadas e visualizações
✅ **Exportação** - Excel, PDF e CSV
✅ **Design Responsivo** - funciona em desktop e mobile

## 🎯 Zonas do Ranking

- 🏆 **TÍTULOS** (1º-3º lugar)
- ⭐ **LIBERTADORES** (4º-12º lugar)
- 🟡 **SUL-AMERICANA** (13º-20º lugar)
- ⚠️ **INTERMEDIÁRIA** (21º-28º lugar)
- 🔴 **REBAIXAMENTO** (29º+ lugar)

## 💾 Armazenamento de Dados

Os dados são puxados diretamente da sua planilha do Google Sheets, garantindo que o site esteja sempre atualizado com as informações mais recentes.

## 🔧 Tecnologias Utilizadas

- HTML5
- CSS3 (com gradientes e efeitos modernos)
- JavaScript (ES6+)
- Chart.js (para gráficos)
- SheetJS (para exportação Excel)
- jsPDF (para exportação PDF)

