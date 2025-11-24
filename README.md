🏭 Automatização de Processo Industrial com Acionamentos Eletrônicos de Motores

Trabalho Final – Acionamento Eletrônico de Motores (AEML8)

<p align="center"> <img src="imgs/banner.png" alt="Banner do Projeto" width="600"> </p> <p align="center"> <a href="https://github.com/MoratoZ/Trabalho-Final-Acionamento-Eletronico-de-Motores-AEML8/stargazers"><img src="https://img.shields.io/github/stars/MoratoZ/Trabalho-Final-Acionamento-Eletronico-de-Motores-AEML8?style=flat-square"></a> <a href="https://github.com/MoratoZ/Trabalho-Final-Acionamento-Eletronico-de-Motores-AEML8/network/members"><img src="https://img.shields.io/github/forks/MoratoZ/Trabalho-Final-Acionamento-Eletronico-de-Motores-AEML8?style=flat-square"></a> <img src="https://img.shields.io/badge/status-completo-4caf50?style=flat-square"> <img src="https://img.shields.io/badge/CLP-Altus%20Nexto%20Xpress-blue?style=flat-square"> <img src="https://img.shields.io/badge/IHM-Altus-orange?style=flat-square"> </p>
📌 Sobre o Projeto

Este repositório reúne o desenvolvimento completo de um processo industrial automatizado para produção de extrato de tomate, utilizando:

CLP Altus Nexto Xpress XP325

IHM programável

Soft-Starters WEG SSW-05

Inversores de Frequência WEG CFW10 e CFW300

Motores de indução trifásicos

O sistema integra sequenciamento, controle de velocidade, alternância de sentidos, instrumentação e operação via IHM — tudo implementado em um painel industrial real no laboratório.

🎥 Demonstração em Vídeo

➡️ Assista ao funcionamento completo do sistema:
https://github.com/MoratoZ/Trabalho-Final-Acionamento-Eletronico-de-Motores-AEML8/blob/main/Demonstra%C3%A7%C3%A3o%20-%20Trabalho%20AEM%20-%20Morato%20-%20-Code%2BDiagramas.mp4

🔧 Arquivos do Repositório
📁 Estrutura Geral
Pasta / Arquivo	Descrição
/Diagramas/	Diagramas de comando e potência usados na montagem prática
/Simulacao/Simulacao_FluidSIM.fssx	Simulação completa do processo no FluidSIM
/CLP/	Código do CLP para o Nexto Xpress
/IHM/	Arquivos do projeto da IHM
/Vídeo/	Demonstração gravada mostrando todo o sistema funcionando
Artigo-TrabalhoFinal.pdf	Artigo apresentado no 16º CONICT 2025 (completo)
⚙️ Tecnologias e Dispositivos Utilizados
🔌 Automação e Controle

CLP Altus Nexto Xpress XP325

IHM com telas para:

Liga/Desliga geral

Diagnóstico de motores

Estado dos sensores

Controle dos inversores

⚙️ Acionamentos Eletrônicos

Partida Estrela–Triângulo (Motor M1)

Soft-Starters SSW-05 (Motores M2 e M4)

Inversor de Frequência CFW10 – modo escalar (Motor M3)

Inversor de Frequência CFW300 – modo vetorial (Motor M5)

🛠️ Equipamentos Complementares

Contatoras, relés, DPS, disjuntores

Fonte 24 Vcc

Sensores e botões físicos

🧪 Fluxo Automatizado do Processo

Lavagem e transporte inicial (M1 – estrela-triângulo)

Abertura e controle de nível do tanque (M2 – Soft-Starter)

Descascamento e transporte reversível (M3 – IF escalar)

Pré-cozimento em estufa (M4 – Soft-Starter)

Batimento, cozimento e esvaziamento final (M5 – IF vetorial)

<p align="center"> <img src="imgs/fluxo_processual.png" width="550"> </p>
📸 Fotos e Interfaces
🔌 Montagem em Painel
<p align="center"> <img src="imgs/painel.jpg" width="550"> </p>
🖥️ Interface da IHM
<p align="center"> <img src="imgs/ihm1.png" width="380"> <img src="imgs/ihm2.png" width="380"> </p>

(Se quiser, posso gerar imagens em SVG desses elementos também!)

📄 Artigo Relacionado

O desenvolvimento deste projeto resultou no artigo apresentado no 16º Congresso de Inovação, Ciência e Tecnologia do IFSP (2025):

📑 Artigo-TrabalhoFinal.pdf

👥 Autores

Gustavo Morato de Marchi Soares

Giovana Campos Lopes

João Victor Dantas dos Santos

⭐ Quer contribuir?

Se quiser usar parte do código, adaptar a lógica ou expandir o processo, fique à vontade!
Contribuições, issues e sugestões são super bem-vindas.
