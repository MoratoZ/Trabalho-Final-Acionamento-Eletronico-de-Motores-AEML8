#🏭 Automatização de um Processo Industrial com Diferentes Métodos de Acionamento Eletrônico de Motores#

Este repositório reúne todos os arquivos do Trabalho Final da disciplina de Acionamento Eletrônico de Motores (AEML8), no qual desenvolvemos a automação completa de um processo industrial para a produção de extrato de tomate, utilizando CLP, IHM e diferentes tipos de acionamentos eletrônicos de motores de indução trifásicos.

O projeto inclui simulação, programação, parametrização de dispositivos reais e a montagem final em painel industrial, integrando lógica de controle, segurança e variação de velocidade.

🚀 Objetivo do Projeto

Implementar um sistema automatizado capaz de controlar cinco motores com diferentes métodos de partida e acionamento:

⭐ Partida estrela–triângulo

⚙️ Soft-Starters

🔄 Inversores de Frequência (escalar e vetorial)

O processo automatizado contempla lavagem, transporte, descascamento, pré-cozimento e batimento/cozimento final do tomate.

📁 Arquivos Disponíveis no Repositório
🧩 Diagramas Elétricos

Diagrama de Comando (001_DIAGRAMA_DE_COMANDO.pdf)

Diagrama de Potência (001_DIAGRAMA_DE_POTENCIA.pdf)
Contêm toda a lógica de acionamento dos motores, intertravamentos, sinalizações e conexões no painel.

🧪 Simulação FluidSIM

Arquivo da simulação (Simulacao_FluidSIM.fssx)
Permite visualizar e testar todo o processo em ambiente virtual, incluindo sensores, temporizações e sequenciamento dos motores.

🖥️ Código do CLP

Programa completo do Nexto Xpress (Codigo_CLP.pro)
Implementa a lógica completa do processo, incluindo temporizações, alternância de sentidos, lógica de segurança e comandos da IHM.

🖱️ Projeto da IHM

Arquivo de Interface Homem–Máquina (Projeto_IHM.tia ou equivalente)
Inclui telas operacionais, botões de comando, indicação de estado dos motores e interação com sensores/temporizadores.

🎥 Vídeo de Demonstração

📌 Link do vídeo no README original — mantido aqui para destaque:
👉 Clique aqui para assistir à demonstração do sistema em funcionamento

🛠️ Tecnologias e Dispositivos Utilizados

CLP: Altus Nexto Xpress XP325

IHM: Interface Touch programável

Motores de Indução Trifásicos (5 unidades)

Inversores de Frequência: WEG CFW10 (escalar) e WEG CFW300 (vetorial)

Soft-Starters: WEG SSW-05

Painel Industrial Completo com contatoras, relés, DPS e disjuntores

📄 Referência Completa

Este projeto também deu origem ao artigo apresentado no 16º CONICT 2025 – IFSP, disponível no repositório:

📄 Artigo-TrabalhoFinal.pdf
