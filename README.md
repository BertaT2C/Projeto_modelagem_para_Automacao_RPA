# Análise do processo de emissão de CTE/MDFE

Para entender rapidamente o processo do usuário, é essencial ter interações significativas. O método de gravação das reuniões de refinamento do processo
desempenha um papel crucial no entendimento da parte funcional do sistema e do trabalho do usuário. Com base nesse critério, foi possível mapear o estado atual do 
processo e identificar quais integrações e melhorias internas poderiam ser aplicadas para a robotização.

# Emissão de CTE e MDFE
Este cliente possui um grande volume de emissões de CTE e MDFE.
O usuário utiliza um coletor de dados e efetua leitura física dos produtos, as informações são integradas com uma "pasta específica no drive". Á partir desse momento o usuário precisa

Passo 1 - Acessar pasta no drive:
- Identificar a filial da empresa
- Efetuar login no Protheus

Passo 2 - Protheus
- Importar arquivo de leitura dentro do sistema para geração do CTE
- Salvar informações da tela de carregamento que geraram os números dos CTEs (Ainda não enviados para a SEFAZ)

*CTE será enviado para a SEFAZ somente após confirmação dos dados do motorista e carga
*Automaticamente os CTEs são integrados com um sistema chamado Chronus (Gestão de logística)

Passo 3 - Protheus - Gerar Manifesto e CTE
- Acessar tela da emissão do Manifesto
- Incluir dados do caminhão e motorista que estão disponívei, pois foram integrados com o sistema Chronus
- Acessar o Chronus, buscar os dados e incluir no Manifesto do Protheus
- Gerar Manifesto
- Enviar CTE para a SEFAZ

*ERP Chronus: tem a determinação do tipo de transporte, código do cavalo, código do motorista relacionado à cada CTE


Foram séries de passos para a emissão de CTE junto ao MDFE e, para simplificar e otimizar esse processo, optei por automatizá-lo utilizando planilhas auxiliares e integrando dados do manifesto diretamente do banco de dados, desenvolvemos um sistema automatizado que executa essas etapas de forma eficiente e precisa.

Empregamos quatro robôs para lidar com diferentes aspectos do processo, garantindo uma execução contínua e sem interrupções. Essa abordagem não apenas acelerou significativamente a emissão de CTE, mas também reduziu a possibilidade de erros humanos e inconsistências nos dados.

Com essa automação, conseguimos aumentar nossa produtividade e eficiência operacional, ao mesmo tempo em que garantimos a conformidade com os requisitos regulatórios.

![FLUXO_CTE MDFE (1) (2) pdf](https://github.com/BertaT2C/Fluxograma_Automacao_RPA/assets/99225701/929d3025-2c22-4d1d-8246-01757e860d71)



![gif-animado-site-em-construcao-31](https://github.com/BertaT2C/Fluxograma_Automacao_RPA/assets/99225701/cf8afc49-36b5-49ae-8e89-adb2efeea45f)
