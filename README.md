🎯 Simulação de Phishing com SEToolkit
Captura de Credenciais em Ambiente Controlado

📌 Visão Geral: Este projeto consiste na simulação de um ataque de phishing utilizando a ferramenta SEToolkit (Social-Engineer Toolkit) em ambiente controlado.
O objetivo é demonstrar, de forma prática, como ataques baseados em engenharia social podem ser estruturados para captura de credenciais, bem como analisar os riscos associados e as estratégias de mitigação.
A simulação foi realizada com fins exclusivamente educacionais, sem qualquer interação com usuários reais.

🎯 Objetivos do Projeto
Compreender o funcionamento de ataques de phishing
Simular captura de credenciais em ambiente controlado
Aplicar conceitos de engenharia social na prática
Documentar o fluxo técnico de execução
Reforçar boas práticas de segurança e prevenção

🧪 Ambiente de Execução: O laboratório foi configurado com acesso à internet para viabilizar o funcionamento da ferramenta:
Sistema operacional: Kali Linux
Ferramenta: SEToolkit
Modo de rede: Bridge Adapter (acesso à rede externa)
Execução em ambiente controlado

🧠 Conceito de Phishing
Phishing é uma técnica de engenharia social que visa enganar usuários para que forneçam informações sensíveis, como credenciais de acesso.Essa abordagem explora principalmente o fator humano, sendo uma das ameaças mais recorrentes em ambientes corporativos.

⚙️ Metodologia Aplicada
A simulação seguiu o fluxo padrão de ataque utilizando o SEToolkit:

Acesso ao ambiente com privilégios administrativos
Inicialização da ferramenta de engenharia social
Seleção de vetores de ataque baseados em páginas web
Utilização do método de captura de credenciais (Credential Harvester)
Clonagem de página legítima para simulação de login
Configuração do ambiente para recepção das credenciais capturadas

🌐 Cenário Simulado
Foi realizada a simulação de uma página de login semelhante à de uma rede social amplamente conhecida, com o objetivo de demonstrar:
Como páginas podem ser clonadas
Como usuários podem ser induzidos a inserir credenciais
Como essas informações podem ser capturadas

📂 Evidências de Execução
As evidências coletadas durante o laboratório incluem:
Inicialização da ferramenta
Página clonada em execução
Captura simulada de credenciais

📊 Resultados Observados
Demonstração prática da eficácia de ataques de engenharia social
Facilidade de replicação de páginas legítimas
Alto risco associado à interação do usuário com links maliciosos
Dependência do fator humano como principal vetor de exploração

🛡️ Medidas de Mitigação:
Com base no cenário simulado, destacam-se as seguintes recomendações:

👤 Conscientização do Usuário
Treinamento em identificação de tentativas de phishing
Verificação de URLs antes de inserir credenciais

🔐 Controles de Acesso
Implementação de autenticação multifator (MFA)
Políticas de senha forte

🌐 Segurança de Rede
Filtros de navegação e bloqueio de domínios suspeitos
Monitoramento de tráfego

🖥️ Proteção de Endpoint
Soluções de segurança com detecção de comportamento
Bloqueio de execução de ferramentas suspeitas

📚 Competências Demonstradas
Engenharia social aplicada à segurança
Uso de ferramentas como SEToolkit
Simulação de ataques em ambiente controlado
Análise de riscos relacionados ao fator humano
Documentação técnica estruturada

⚠️ Considerações Éticas: Este projeto foi desenvolvido exclusivamente para fins educacionais, em ambiente controlado.Nenhum dado real foi coletado e nenhuma interação com usuários reais foi realizada.

🚀 Possíveis Evoluções
Simulação de campanhas de phishing mais elaboradas
Integração com análise de logs e detecção
Testes com conscientização de usuários
Simulação de resposta a incidentes
