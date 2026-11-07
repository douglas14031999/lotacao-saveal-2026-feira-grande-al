# SAVEAL 2026 · Consulta do Aplicador · Feira Grande - AL

Sistema de consulta de cronograma e lotação dos aplicadores do **SAVEAL 2026** no município de Feira Grande - AL.

🌐 **Acesse online:** [https://douglas14031999.github.io/lotacao-saveal-2026-feira-grande-al/](https://douglas14031999.github.io/lotacao-saveal-2026-feira-grande-al/)

---

## 📋 Funcionalidades

- **Consulta por CPF:** Permite que o aplicador consulte suas escolas, turmas, turnos e salas atribuídas.
- **Filtros e Detalhamento:**
  - Identificação de escolas municipais e rede estadual.
  - Alocação por data de aplicação.
  - Salas extras e alunos especiais.
- **Interface Responsiva:** Design otimizado para celulares e computadores, com suporte automático ao tema claro e escuro.

---

## 🌐 Configuração de Subdomínio Personalizado (Hostinger / DNS)

Para vincular um subdomínio da Hostinger a este projeto:

1. **Hostinger (hPanel):**
   - Acesse **Domínios** -> selecione seu domínio -> **DNS / Servidores de Nomes**.
   - Adicione um registro:
     - **Tipo:** `CNAME`
     - **Nome:** prefixo do subdomínio (ex: `saveal` para `saveal.seudominio.com.br`)
     - **Aponta para:** `douglas14031999.github.io`
     - **TTL:** `14400` (ou padrão)
2. **GitHub Pages:**
   - Adicione o arquivo `CNAME` com o subdomínio completo na raiz deste repositório (ou configure em *Settings > Pages > Custom domain*).
   - Ative a opção **Enforce HTTPS** após a propagação do DNS.

---

## 🚀 Como Executar Localmente

Basta abrir o arquivo `index.html` em qualquer navegador web:

```bash
# Clone o repositório
git clone https://github.com/douglas14031999/lotacao-saveal-2026-feira-grande-al.git

# Acesse o diretório
cd lotacao-saveal-2026-feira-grande-al

# Abra o index.html no navegador padrão (Windows)
start index.html
```
