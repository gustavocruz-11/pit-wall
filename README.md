# 🏎️ Pit Wall · GP de São Paulo F1

**Desenvolvido por:** Gustavo Cruz  

Interface web temática de Fórmula 1 desenvolvida em **HTML5** e **CSS3** puro, dedicada ao Grande Prémio de São Paulo no Autódromo de Interlagos. O projeto apresenta o grid de pilotos, tabela de classificação interativa estilo placar televisivo e formulário de reserva de ingressos.

---

## 📌 Sobre o Projeto

O **Pit Wall** é uma *landing page* moderna e responsiva inspirada nas transmissões oficiais da Fórmula 1. A identidade visual combina fundo escuro (*dark mode*), tipografia desportiva (`Titillium Web`), divisórias estilizadas em formato de zebra de pista e paletas de cores dinâmicas atribuídas a cada escuderia.

---

## 🚀 Funcionalidades e Secções

- 🧭 **Barra de Navegação Fixa (`topbar`):** Logótipo estilizado, links de ancoragem com rolagem suave (`scroll-behavior: smooth`) e botão de chamada para ação (CTA).
- 🏁 **Banner Principal (`hero`):** Destaque do evento (Autódromo de Interlagos · Novembro de 2026) com faixa diagonal em gradiente, imagem de fundo e painel de telemetria rápida da pista (71 voltas, 4.309 km e 15 curvas).
- 🛣️ **Zebra da Pista (`kerb`):** Separador visual criado exclusivamente com CSS (`repeating-linear-gradient`).
- 🏎️ **Grid de Pilotos (`#pilotos`):** Cartões responsivos em grade (`CSS Grid`) com identificação visual por equipa (Ferrari, McLaren, Mercedes e Audi) e numeração estilizada
- 🏆 **Classificação (`#classificacao`):**
  - Barra de filtros por nome de piloto ou equipa.
  - Tabela estilo placar de TV com destaque especial para o líder do campeonato e barras coloridas indicativas de cada construtor
- 🎟️ **Ingressos (`#ingressos`):**
  - Layout dividido em duas colunas com tabela de preços por setor (Arquibancada A, Setor da Reta e Box VIP) e alerta de lotação
  - Formulário completo de reserva com campos para dados pessoais, escolha de setor, data, quantidade, upload de foto para o telão e mensagem de apoio

---

## 📁 Estrutura de Ficheiros

```text
.
├── index_2.html    # Estrutura semântica e conteúdo da página
├── style.css       # Folha de estilos, variáveis de equipas e responsividade
└── img/            # Diretório de imagens (banner de fundo)
