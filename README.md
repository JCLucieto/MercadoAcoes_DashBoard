# MercadoAcoes_DashBoard

## Análise do Mercado de Ações Nasdaq e NYSE

### Contexto  
Com o início de um novo período de governo de Donald Trump nos Estados Unidos e motivado por suas 
declarações no dia da posse (21.01.2025) sobre medidas para a área de Tecnologia, especialmente em 
relação à Inteligência Artificial, iniciei um trabalho de coleta, preparação e análise de dados do 
mercado de ações das principais empresas de tecnologia que operam na Nasdaq e na Bolsa de Valores 
de Nova York (NYSE).
Este trabalho está dividido em duas fases, com a primeira fase sendo a análise do mercado de ações 
dessas empresas durante o governo de Joe Biden e a segunda fase, que ocorrerá no final do governo 
Trump, analisando como essas empresas se comportaram comparativamente ao período do governo anterior.
Portanto, este trabalho abrange, na Fase 1, o período de governo de Joe Biden (20.01.2021 a 20.01.2025), 
e na Fase 2, abrangerá o período de governo de Trump (21.01.2025 a 20.01.2029).

### Metodologia e Ferramentas  
O trabalho para construção da  Fase 1 está dividido em 2 etapas:
- Etapa 1 - Captura, Tratamento e Preparação dos Dados (desenvolvida utilizando notebook Jupyter com Python e Pandas)
- Etapa 2 - Análise e Visualização dos Dados (desenvolvida utilizando Power BI).

### Acesso pelo GitHub  
O material completo deste trabalho (arquivos de dados (.csv), notebook (.ipynb) e relatório Power BI (.pbix)) está disponível 
para consulta e livre utilização no GitHub - https://github.com/JCLucieto/MercadoAcoes_DashBoard.git

### Acesso pelo Power BI  
Esse trabalho também pode ser acessado por quem tem uma conta Power BI (https://app.powerbi.com).
Acesse gratuitamente por 60 dias através do Microsoft Fabric Free.
Abaixo você encontra o link para esse relatório :
https://app.powerbi.com/links/xqaMuf96m1?ctid=2f112f84-2ad4-4280-a7bf-c2af515a2c36&pbi_source=linkShare  

### Empresas Analisadas  
As 12 principais empresas de tecnologia listadas na NASDAQ e na Bolsa de Valores de Nova York (NYSE) são algumas das maiores e mais influentes do setor, com forte presença no mercado global.  
Elas incluem gigantes de várias áreas da tecnologia, como hardware, software, e-commerce, inteligência artificial, entre outros.  
Este trabalho traz uma análise sobre as ações dessas empresas, com base em seu valor de mercado e impacto na indústria.  

**NASDAQ (National Association of Securities Dealers Automated Quotations)**  

Apple (AAPL) – Líder em eletrônicos, como iPhones, iPads, Macs, e também no setor de serviços, com iCloud e Apple Music.  
Microsoft (MSFT) – Conhecida por seus softwares como o Windows e Office, além de sua plataforma de nuvem Azure.  
Alphabet (GOOGL) – Controladora do Google, YouTube, Android e outros produtos e serviços relacionados à internet.  
Amazon (AMZN) – Gigante do e-commerce e também com forte atuação em cloud computing (AWS) e inteligência artificial.  
NVIDIA (NVDA) – Líder em chips gráficos (GPUs) e inovação em áreas como inteligência artificial e jogos.  
Meta (META) – Anteriormente conhecida como Facebook, é a maior rede social do mundo e está se expandindo para o metaverso.  
Tesla (TSLA) – Conhecida por seus carros elétricos, mas também envolvida em energias renováveis e armazenamento de energia.  
Intel (INTC) – Principal fabricante de semicondutores, com chips para computadores, servidores e dispositivos móveis.  
Adobe (ADBE) – Desenvolvedora de softwares para criação e edição de imagens, vídeos e design gráfico (Photoshop, Illustrator, etc.).  
PayPal (PYPL) – Plataforma de pagamentos online, incluindo serviços como Venmo e Xoom.  

**NYSE (New York Stock Exchange)**  

IBM (IBM) – Pioneira em computadores e tecnologia, hoje focada em inteligência artificial e soluções corporativas de TI.  
Oracle (ORCL) – Especialista em software corporativo, bancos de dados e soluções de nuvem.   

Essas empresas dominam a tecnologia global, abrangendo diversos aspectos do mercado, desde dispositivos e software até serviços 
de nuvem e soluções financeiras. Cada uma delas tem um impacto significativo na transformação digital e na economia mundial.

### Fonte de Dados  
Os dados utilizados neste trabalho foram coletados no site da NASDAQ.  
URL   : https://www.nasdaq.com  
Mapa : Market Activity - Stocks - Common Stock - Historical Quotes (Download Historical Data)  

### Tipo de Dados  
Foram coletados arquivos no formato CSV (um arquivo para cada empresa) com o movimento diário (Série Temporal) dos últimos 5 anos.

### Informações Tratadas  
Este trabalho utiliza as seguintes informações existentes nos arquivos:
- Data da Negociação
- Valor na Abertura
- Valor Mínimo Atingido
- Valor Máximo Atingido
- Valor no Fechamento
- Volume Negociado
