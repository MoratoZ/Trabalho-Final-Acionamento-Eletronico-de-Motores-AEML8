<svg width="1400" height="320" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="100%"><stop offset="0%" style="stop-color:#001f3f;stop-opacity:1" /><stop offset="40%" style="stop-color:#003b6f;stop-opacity:1" /><stop offset="100%" style="stop-color:#009dff;stop-opacity:1" /></linearGradient></defs><rect x="0" y="0" width="1400" height="320" fill="url(#grad)" /><circle cx="250" cy="160" r="200" fill="#33cfff22" /><circle cx="1150" cy="100" r="240" fill="#00eaff18" /><circle cx="700" cy="200" r="180" fill="#9be7ff15" /><rect x="0" y="40" width="1400" height="3" fill="#00c8ff66" /><rect x="0" y="100" width="1400" height="3" fill="#00c8ff66" /><rect x="0" y="260" width="1400" height="3" fill="#00c8ff66" /><rect x="10" y="10" width="1380" height="300" fill="none" stroke="#00eaff" stroke_width="4" rx="18" /><text x="700" y="150" fill="#e6f7ff" style="font-size:70px;font-family:Segoe UI Black;text-anchor:middle;dominant-baseline:middle;text-shadow:3px 3px 12px #009dff;letter-spacing:1px;"> </text><text x="700" y="225" fill="#9be7ff" style="font-size:36px;font-family:Segoe UI;text-anchor:middle;dominant-baseline:middle;opacity:0.85;letter-spacing:0.5px;"> </text></svg>
![banner](https://github.com/user-attachments/assets/ab819389-bf62-4d24-b23f-7d26c2da7f03)

<h1 style="font-size: 60px; text-align: center;">
🏭 Automatização de um Processo Industrial com Diferentes Métodos de Acionamento Eletrônico de Motores
</h1>

Este repositório reúne todos os arquivos do Trabalho Final da disciplina de Acionamento Eletrônico de Motores (AEML8), no qual desenvolvemos a automação completa de um processo industrial para a produção de extrato de tomate, utilizando CLP, IHM e diferentes tipos de acionamentos eletrônicos de motores de indução trifásicos.

O projeto inclui simulação, programação, parametrização de dispositivos reais e a montagem final em painel industrial, integrando lógica de controle, segurança e variação de velocidade.

<h2 style="font-size: 40px; color:#e63946;">
🚀 Objetivo do Projeto
</h2>
Implementar um sistema automatizado capaz de controlar cinco motores com diferentes métodos de partida e acionamento:
  - ⭐ Partida estrela–triângulo
  - ⚙️ Soft-Starters
  - 🔄 Inversores de Frequência (escalar e vetorial)

O processo automatizado contempla lavagem, transporte, descascamento, pré-cozimento e batimento/cozimento final do tomate.

<h2 style="font-size: 40px; color:#e63946;">
📁 Arquivos Disponíveis no Repositório
</h2>

<h3 style="font-size: 25px; color:#e63946;">
🧩 Diagramas Elétricos
</h3>
Diagrama de Comando e Diagrama de Potência - contêm toda a lógica de acionamento dos motores, intertravamentos, sinalizações e conexões no painel.
> Diagramas-AutoCAD.dwg

<h3 style="font-size: 25px; color:#e63946;">
🧪 Simulação FluidSIM
</h3>
Arquivo da simulação - permite visualizar e testar todo o processo em ambiente virtual, incluindo sensores, temporizações e sequenciamento dos motores.
> Simulação-FluidSIM.ct

<h3 style="font-size: 25px; color:#e63946;">
🧪 Simulação CADeSIMU
</h3>
Arquivo da simulação - permite visualizar e testar a maior parte do processo em ambiente virtual.
> Simulação-CADeSIMU

<h3 style="font-size: 25px; color:#e63946;">
🖥️ Código do CLP
</h3>
Programa completo do Nexto Xpress - implementa a lógica completa do processo, incluindo temporizações, alternância de sentidos, lógica de segurança e comandos da IHM.
> ProjetoFinal-CLP.project

<h3 style="font-size: 25px; color:#e63946;">
🖱️ Projeto da IHM
</h3>
Arquivo de Interface Homem–Máquina - inclui telas operacionais, botões de comando, indicação de estado dos motores e interação com sensores/temporizadores.
> ProjetoFinal-IHM.neoproj

<h2 style="font-size: 40px; color:#e63946;">
🎥 Vídeo de Demonstração
</h2>
👉 Clique aqui para assistir à demonstração do sistema em funcionamento: `https://www.youtube.com/watch?v=GOhv41bhNo8`

<h2 style="font-size: 40px; color:#e63946;">
🛠️ Tecnologias e Dispositivos Utilizados:
</h2>
- CLP: Altus Nexto Xpress XP325
- IHM: Interface Touch programável
- Motores de Indução Trifásicos (5 unidades)
- Inversores de Frequência: WEG CFW10 (escalar) e WEG CFW300 (vetorial)
- Soft-Starters: WEG SSW-05
- Painel Industrial Completo com contatoras, relés, DPS e disjuntores

<h2 style="font-size: 40px; color:#e63946;">
📄 Referência Completa
</h2>
Este projeto também deu origem ao artigo disponível no repositório:
> 📄 Artigo-TrabalhoFinal.pdf
