# 🎮 Software QA Testing Portfolio 🎮

Boas-vindas ao meu portfólio profissional de **Quality Assurance (QA) focado em Games**. 

Sou apaixonado por videogames desde a infância quando ganhei meu primeiro videogame, um Dynavision, após a época de soprar muitas fitas (rsrs), migrei para a inesquecível geração do PlayStation 2, depois passei pelas gerações do PlayStation 3, PSP e Xbox One, até chegar ao PC, onde jogo atualmente. Transformei meu maior hobby em foco profissional ao unir o entusiasmo pelos games à disciplina do Quality Assurance.

Minha trajetória combina um olhar analítico afiado para identificar falhas com o compromisso de garantir a melhor experiência possível para os jogadores. Este portfólio reflete essa união entre técnica, atenção aos detalhes e paixão pela indústria de jogos.

Este repositório reúne relatórios de bugs (*Bug Reports*) estruturados sob padrões da indústria, cobrindo testes funcionais, visuais, de física e de sistemas em diferentes plataformas (PC e Consoles).

---

## 🛠️ Metodologia e Estrutura dos Relatórios

Cada relatório foi documentado utilizando um modelo padronizado de QA, contendo:
* **Classificação Técnica:** Severidade e Prioridade baseadas no impacto da jogabilidade.
* **Ambiente e Reprodutibilidade:** Detalhes de plataforma, versão/build e passos objetivos para reprodução.
* **Análise de Resultados:** Comparativo claro entre *Resultado Esperado* e *Resultado Atual*.
* **Evidências Mapeadas:** Mídias e telas armazenadas na pasta central `/imagens`.

---

## 📑 Índice de Bug Reports / Bug Reports Index

| Jogo / Game | Tipo de Bug / Issue Type | Gravidade / Severity | Português | English |
| :--- | :--- | :--- | :---: | :---: |
| **Overwatch** | Matchmaking / Achievement Exploit | Média | [Ver Relatório](games/Overwatch-pt.md) | [Read Report](games/Overwatch-en.md) |
| **Pimbolas** | Physics / Despawn Glitch | Média | [Ver Relatório](games/Pimbolas-pt.md) | [Read Report](games/Pimbolas-en.md) |
| **Call of Duty: MW2 (2022)** | Visual / Environment Clipping | Baixa | [Ver Relatório](games/Call_of_Duty_MW2_2022-pt.md) | [Read Report](games/Call_of_Duty_MW2_2022-en.md) |
| **Assassin's Creed Unity** | Graphics / Texture Streaming Failure | Alta | [Ver Relatório](games/Assassin's_Creed_Unity-pt.md) | [Read Report](games/Assassin's_Creed_Unity-en.md) |
| **Speedy Eggbert** | Physics / Collision Clipping | Baixa | [Ver Relatório](games/Speedy_Eggbert-pt.md) | [Read Report](games/Speedy_Eggbert-en.md) |
| **League of Legends** | Mechanics / Infinite Stat Stacking | Crítica | [Ver Relatório](games/League_of_Legends-pt.md) | [Read Report](games/League_of_Legends-en.md) |

---

## 📁 Estrutura do Repositório

```text
game-qa-bug-reports/
├── README.md
├── imagens/
│   ├── overwatch.png
│   ├── overwatch_menu_antigo.png
│   ├── pimbolas.png
│   ├── codmw2_2022.png
│   ├── ac_unity.png
│   ├── ac_unity1.png
│   ├── ac_unity2.png
│   ├── ac_unity3.png
│   ├── speedy_eggbert.png
│   └── lol_guinsoo.png
└── games/
    ├── overwatch-pt.md
    ├── overwatch-en.md
    ├── Pimbolas-pt.md
    ├── Pimbolas-en.md
    ├── Call_of_Duty_MW2_2022-pt.md
    ├── Call_of_Duty_MW2_2022-en.md
    ├── Assassin's_Creed_Unity-pt.md
    ├── Assassin's_Creed_Unity-en.md
    ├── Speedy_Eggbert-pt.md
    ├── Speedy_Eggbert-en.md
    ├── League_of_Legends-pt.md
    └── League_of_Legends-en.md
