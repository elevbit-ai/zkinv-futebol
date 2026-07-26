# Zkinv - Previsor de Partidas de Futebol

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white)

**Ferramenta de análise preditiva de partidas de futebol com inteligência artificial.**

[Live Demo](https://usacomment.com) · [Report Bug](https://github.com/elevbit-ai/zkinv-futebol/issues)

</div>

---

## Funcionalidades

- **Análise Preditiva com IA** — Previsões de resultados de partidas de futebol
- **Gráficos Interativos** — Visualização de desempenho com Chart.js
- **Dados Gerados por IA** — Estatísticas realistas para times e confrontos
- **Relatórios em PDF** — Exportação completa de análises preditivas
- **Análise Quantitativa** — Probabilidades de vitória, empate e derrota
- **Confronto Direto (H2H)** — Histórico de partidas entre os times
- **Interface Temática** — Design neon cyberpunk com animações

## Como Funcionar

### Configuração da API

1. Obtenha uma chave de API do [Google Gemini](https://aistudio.google.com/app/apikey)
2. Insira a chave no campo "Chave da IA Gemini"
3. Clique em "Salvar Chave" — ela será armazenada localmente no navegador

### Análise de Partidas

1. Digite o nome do time (ex: Flamengo, Corinthians, Palmeiras)
2. Clique em "Gerar Análise"
3. Aguarde a geração de dados e análise preditiva
4. Visualize o gráfico e o relatório completo

### Relatório Preditivo

O sistema gera um relatório completo com:
- **Probabilidade de Vitória** (time da casa)
- **Probabilidade de Empate**
- **Probabilidade de Vitória** (visitante)
- **Justificativa Técnica** (análise detalhada)
- **Resultado Mais Provável**

## Dados Analisados

| Dado | Descrição |
|------|-----------|
| Forma Recente | Sequência de resultados (W/D/L) |
| Média de Gols | Gols marcados e sofridos por jogo |
| Confronto Direto | Histórico de partidas entre os times |
| Desempenho Geral | Jogos disputados e estatísticas |

## Stack Tecnológica

- **Frontend:** HTML5, Tailwind CSS, JavaScript Vanilla
- **Gráficos:** Chart.js
- **PDF:** jsPDF
- **API:** Google Gemini (gemini-2.5-flash-preview-05-20)
- **Design:** Tema neon cyberpunk com gradientes animados

## Instalação

Sem instalação necessária. Abra `index.html` em qualquer navegador moderno.

```bash
git clone https://github.com/elevbit-ai/zkinv-futebol.git
cd zkinv-futebol
open index.html
```

## Estrutura do Projeto

```
zkinv-futebol/
├── index.html      # Aplicação principal (HTML único)
├── README.md       # Documentação do projeto
├── LICENSE         # Licença MIT
└── .gitignore      # Arquivos ignorados
```

## Contribuindo

Contribuições são bem-vindas! Sinta-se à livre para enviar um Pull Request.

1. Faça o fork do projeto
2. Crie sua branch (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adicionar nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## Autor

**Joaquim Pedro de Morais Filho**

- Website: [USAcomment.com](https://usacomment.com)
- Email: j360074@hotmail.com
- GitHub: [@elevbit-ai](https://github.com/elevbit-ai)

## Aviso Legal

Este sistema é uma ferramenta de estudo e **não representa recomendação de aposta**. Todas as previsões são baseadas em dados gerados por inteligência artificial para fins demonstrativos.

## Doação

Se este projeto foi útil para você, considere fazer uma doação via PIX:

```
00020101021126370014br.gov.bcb.pix0115pagamento@bk.ru5204000053039865802BR5925Joaquim Pedro De Morais F6009Sao Paulo62070503***63043A02
```

---

<div align="center">

Feito com precisão por **Joaquim Pedro de Morais Filho**

</div>
