# 💎 Inteligência de Mercado - Edição Preta (Platinum & Enterprise)

![Status](https://img.shields.io/badge/Status-Estável-brightgreen)
![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Dramaturgo](https://img.shields.io/badge/Engine-Playwright-orange)
![Licença](https://img.shields.io/badge/License-Proprietária-red)

O **Inteligência de Mercado** é uma solução avançada de monitoramento de preços e análise de dados para comércio eletrônico. Desenvolvido para suprir a necessidade de lojistas e mineradores de hardware, o software automatiza a coleta de preços, calcula indicadores de mercado (KPIs) e gera relatórios estratégicos em tempo real.

---

## 🚀 Funções Principais

### 🔹 Versão Platinum (Manual)
- **Extração Ultra-Rápida:** Motor otimizado para sites dinâmicos (Pichau, Terabyte, etc) usando Playwright.
- **Modo furtivo:** Proteção contra blocos e detecção de bots integrados.
- **Painel de KPIs:** Visualização instantânea de Menor Preço, Média de Mercado e Sugestão de Revisão (margem de 25%).
- **Exportação Dual:** Geração automática de relatórios em **Excel (.xlsx)** e **CSV**.

### 🔹 Versão Enterprise (Premium)
- **Agendamento Diário:** Defina um horário e o software realiza a busca de forma autônoma.
- **Segundo Plano (Bandeja do Sistema):** O aplicativo ópera de forma silenciosa na bandeira do Windows, sem ocupar espaço na barra de tarefas.
- **Inicialização automática:** Operação para iniciar automaticamente com o Windows.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3.10+
- **Interface Gráfica:** Tkinter (Design personalizado da edição preta)
- **Raspagem da Web:** Dramaturgo + Dramaturgo-Furtividade
- **Análise de Dados:** Pandas
- **Manipulação de Planilhas:** Openpyxl e XlsxWriter
- **Automação:** Horário e Pystray
