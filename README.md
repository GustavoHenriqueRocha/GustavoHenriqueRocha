### Gustavo Henrique

Desenvolvedor de automação industrial e back-end em Aparecida de Goiânia (GO).
Conecto máquinas de fábrica a sistemas web e ao ERP.

#### 🏭 Ekoplastic / Nexapack — indústria de embalagens plásticas
Desenvolvo praticamente sozinho os sistemas internos da fábrica:

- **1.300+ commits em 6 meses** no sistema principal, que integra a produção ao ERP **Bling** (etiquetas, pesagem, lotes e turnos)
- **Leitura de máquinas 24/7** — extrusoras, dosadores e sacoleiras via **Modbus TCP/RTU** (CLP WEG PLC300, IHM Weintek, controladores Gefran), com painéis web em tempo real e alertas
- **Alta disponibilidade** — servidor principal e reserva que assume sozinha quando o principal cai, túnel até a nuvem e backup automático com restic
- **Ponto eletrônico** — leitura do AFD do relógio Topdata Inner Rep e cálculo de jornada
- **8 repositórios** com o código versionado da operação

#### 📈 Destaques (medidos em produção)
| | Antes | Depois |
|---|---|---|
| Abrir o painel de produção | até 124 s | < 0,1 s |
| Publicação dos dashboards (p90) | 41,7 s | 2,7 s |
| Erros 429 da API do ERP | ~5.800 / semana | −94% (rate limiter distribuído entre processos) |
| Telemetria da extrusora | 1 leitura / 3,3 s | ~1 leitura / s |
| Monólitos de 6–14 mil linhas | 1 arquivo | módulos, sem mudar 1 byte da saída (golden master) |
| Testes automatizados | — | 2.100+ (pytest e Playwright), com portões em git hooks e deploy com rollback |

#### 🎮 Projetos pessoais
- **[modbus-painel](https://github.com/GustavoHenriqueRocha/modbus-painel)** — leitura Modbus TCP em Python puro e painel web ao vivo configurado por TOML, com simulador para testar sem CLP. Somente leitura, sem dependências
- **[TriAevum-Switch](https://github.com/GustavoHenriqueRocha/TriAevum-Switch)** — port nativo de *Zelda: Ocarina of Time 3D* (recompilado) para Nintendo Switch homebrew. Minha parte: backend gráfico **deko3d**, frame time estável a 60 fps e testes de regressão
- **[pula-anuncio](https://github.com/GustavoHenriqueRocha/pula-anuncio)** — controle remoto pelo celular: touchpad, teclado e pular anúncio do YouTube sozinho (Linux/Hyprland e Windows)

#### 🧰 Tecnologias
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Modbus](https://img.shields.io/badge/Modbus-555555?style=flat)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat&logo=windows&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

#### 📊 Estatísticas
![Estatísticas](https://github-readme-stats.vercel.app/api?username=GustavoHenriqueRocha&show_icons=true&count_private=true&hide_border=true)
![Linguagens](https://github-readme-stats.vercel.app/api/top-langs/?username=GustavoHenriqueRocha&layout=compact&hide_border=true)
