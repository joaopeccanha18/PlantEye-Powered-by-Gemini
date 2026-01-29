# PlantEye-Powered-by-Gemini
A AI assistant to help you a care your plants.
PlantEye 2.0 - IA de Acessibilidade Botânica
O PlantEye é um assistente inteligente focado em inclusão. Ele utiliza a visão multimodal do Google Gemini para auxiliar pessoas com deficiência visual ou auditiva no cuidado de plantas, oferecendo monitoramento contínuo ou consultas sob demanda.

♿ Acessibilidade em Primeiro Lugar
Deficiência Visual: Descrições detalhadas em áudio via Text-to-Speech (React) sobre o estado de saúde, cor das folhas e necessidades de rega.

Deficiência Auditiva: Interface de alto contraste com legendas em tempo real e indicadores visuais claros sobre diagnósticos da planta.

🕹️ Modos de Operação
Monitoramento em Tempo Real: Fluxo contínuo de análise onde a IA interage com o usuário conforme detecta mudanças sutis na planta.

Modo Manual (Snapshot): O usuário aciona um comando para capturar um quadro específico da câmera. A IA realiza uma varredura profunda e dita/exibe todos os dados técnicos e dicas de cuidado.

🛠️ Tecnologias
Core: React (Interface e Falas) e TypeScript (Lógica e Tipagem).

IA: Google Gemini API (Visão Multimodal).

Estrutura: HTML5 Semântico para leitores de tela.

🚀 Início Rápido
Pré-requisito: Ter o Node.js instalado.

Instalação: npm install

Configuração: Em .env.local, adicione: GEMINI_API_KEY=sua_chave_aqui

Execução: npm run dev

👁️‍🗨️ Interação com a IA
Diferente de sensores comuns, o PlantEye permite uma conversa. O usuário pode perguntar via voz ou texto: "O que são essas manchas amarelas?", e o sistema responde analisando visualmente o problema em tempo real.
