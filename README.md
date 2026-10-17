# 🌸 FinCockpit • Gestão & Produtividade Financeira

Aplicação web executiva e elegante voltada para gestão diária de tarefas, rotina financeira recorrente, cronograma temporal e ferramentas de cálculo financeiro.

---

## 🚀 Como Fazer o Deploy no Vercel em 2 Minutos

O projeto é 100% estático (HTML, CSS e JS puros via CDN), configurado diretamente pelo arquivo `vercel.json`.

### Opção 1: Via GitHub & Vercel Dashboard (Recomendado)

1. **Suba este projeto para um repositório no seu GitHub**:
   - Crie um novo repositório no GitHub (ex: `fincockpit`).
   - Faça o commit e push dos arquivos desta pasta (`index.html`, `vercel.json`, `.gitignore`, `README.md`).
2. **Conecte com o Vercel**:
   - Acesse [vercel.com](https://vercel.com) e faça login.
   - Clique em **"Add New..."** > **"Project"**.
   - Selecione o repositório `fincockpit` da sua lista.
   - Em **Framework Preset**, deixe selecionado **"Other"**.
   - Em **Build and Output Settings**, deixe todas as opções de override **desativadas (OFF)**.
   - Clique em **"Deploy"**.
3. **Pronto!** Em menos de 10 segundos seu link HTTPS estará online (ex: `https://fincockpit.vercel.app`).

---

### Opção 2: Direto pelo Vercel CLI (Via Terminal)

Se preferir subir direto pelo terminal:

1. Instale o Vercel CLI:
   ```bash
   npm i -g vercel
   ```
2. Na pasta do projeto, execute:
   ```bash
   vercel --prod
   ```

---

## ✨ Recursos Inclusos

- **Painel Cockpit (Visão Geral)**: KPIs diários, acompanhamento de prioridades, notas rápidas e rotinas diárias.
- **Atividades Diárias Constantes**: Gestão completa de rotinas fixas de todo dia, com liberdade para adicionar, editar e retirar demandas a qualquer momento.
- **Cronograma Temporal (Dia • Mês • Ano)**: Calendário mensal interativo e histórico anual.
- **Gerenciador Corporativo de Tarefas**: Cadastro completo por categoria, vencimento e prioridade.
- **Checklist do Dia**: Foco diário com barra de progresso em tempo real.
- **Calculadoras Financeiras**: Juros e multas por atraso, variação percentual (MoM/YoY) e desconto comercial.
- **Modo Claro / Modo Escuro** com paleta azul suave, feminina e profissional.
- **Persistência Total Local**: Todos os dados ficam salvos com segurança no navegador via `localStorage`.
- **Compatibilidade Mobile & Desktop**: Drawer deslizante em smartphones e sidebar fixa em computadores.

