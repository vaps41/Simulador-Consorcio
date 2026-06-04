Simulador de Consórcio - Lei 11.795/2008 🏛️📊

Um simulador web interativo construído em React e Tailwind CSS para calcular, comparar e analisar os custos reais de consórcios no Brasil, seguindo as diretrizes da Lei nº 11.795/2008 (Lei dos Consórcios).

🚀 Funcionalidades

Cálculo de Custo Efetivo: Descubra o valor real pago em taxas de administração e fundo de reserva, sem a ilusão de "zero juros".

Categorias Dinâmicas: Simulações otimizadas para Veículos, Imóveis, Serviços e Eletroeletrônicos.

Filtros Inteligentes: Busque administradoras por região de atuação (Nacional, Sul, Sudeste, etc.) e filtre apenas por instituições com selo de confiabilidade do Banco Central.

Métricas de Saúde do Grupo: Ordene as instituições pelo menor custo, maior índice de contemplação (sorteios) ou menor taxa de inadimplência.

Integração com Dados do BACEN: Capacidade de ler planilhas oficiais de dados abertos para gerar o ranking dinamicamente com as taxas praticadas no mês atual.

🛠️ Tecnologias Utilizadas

HTML5 & CSS3

React 17 (via CDN, sem necessidade de build/Node.js)

Babel Standalone (para compilação JSX no navegador)

Tailwind CSS (via CDN)

Lucide Icons (ícones vetoriais)

⚙️ Como Executar o Projeto

O projeto foi construído para ser "plug and play". Por ser um aplicativo Single-File Component, você não precisa instalar nenhuma dependência ou rodar servidores complexos.

Faça o download ou copie o código do arquivo index.html.

Dê um duplo clique no arquivo para abri-lo em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).

Pronto! O simulador já está funcionando com os dados estimativos padrão.

⚠️ IMPORTANTE: Como importar dados reais do Banco Central (BACEN)

Para utilizar a funcionalidade avançada de "Planilha Consolidada" e fazer com que o simulador calcule o Top 5 usando os dados oficiais e mais recentes do mercado, você deve seguir estes passos:

Acesse o portal de Dados Abertos de Consórcios do Banco Central:
🔗 https://www.bcb.gov.br/estabilidadefinanceira/consorciobd

Na página, procure pelos relatórios mensais.

Atenção: Você DEVE baixar o arquivo referente aos Dados Consolidados (por exemplo, o arquivo agrupado de Bens Móveis - Grupos ou similar no formato .csv).

Nota: O sistema não funcionará se você baixar os relatórios de "Reclamações" ou dados não estruturados de cotas individuais. O arquivo precisa ser a consolidação dos grupos de consórcio.

Salve o arquivo em seu computador (ex: 202603Bens_Moveis_Grupos.csv).

Abra o simulador no navegador, vá até a seção "Planilha Consolidada" na coluna esquerda, clique no botão de envio de arquivo e selecione o .csv que você acabou de baixar.

O sistema lerá as colunas de "Taxa de Administração" e "Administradora" automaticamente, gerando um novo ranking oficial e extraindo a média tarifária de cada empresa!

📜 Licença

Este é um projeto educativo desenvolvido para facilitar o entendimento financeiro sobre os custos envolvendo as cartas de crédito no Brasil. Sinta-se livre para modificar, estudar e aprimorar.
