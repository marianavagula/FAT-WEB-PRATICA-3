✅✅Apresentação:
Olá, sou a Mariana da Silva Vagula e estou realizando o curso de Programação Web de 120 horas pela FAT no ano de 2025.

✅✅Objetivo e observações: 
Esse código foi desenvolvido no módulo 1 e é a atividade prática 3 da aula 8.
Criei um site de uma padaria qualquer e a minha chama "Padaria da Mariana".
O site possui 5 html pois foi solicitado que o aluno crie um html para cada página da padaria.
Estamos na etapa de estruturação, então o código só possui o html.

✅✅Estrutura do projeto:
🔸index.html
Tabela de Cardápio: Com Categoria, Produto, Descrição e Preço.
Tabela de Horários: Detalhando os dias e horários de funcionamento.
Mínimo de 5 imagens de alta qualidade (produtos, ambiente) e seções organizadas (ex: Produtos, Ambiente, Equipe).
Um vídeo institucional ou demonstrativo incorporado na página.
Estrutura de pastas lógica e nomes de arquivos padronizados.
Implementação de atributos de acessibilidade (alt, etc).
Documentação atualizada do projeto (README.txt)

🔸contato.html
Missão: Criar o principal canal de comunicação. Deve ser simples, direto e funcional.
Campos obrigatórios:
👤 Nome completo (input text, required)
📧 Email (input email, required)
📋 Assunto (select com opções)
✍️ Mensagem (textarea, required, mínimo 10 caracteres)
Campo opcional:
📞 Telefone (input tel, com pattern)

🔸pedidos.html
Missão: Permitir que o cliente personalize um pedido complexo de forma clara e organizada.
Seção 1 - Dados do Cliente:
👤 Nome completo (required)
📞 Telefone (required, com pattern)
📧 Email (required)
Seção 2 - Detalhes do Pedido:
🍰 Tipo de produto (radio buttons): Bolo, Torta, Salgados
🍫 Sabor/Recheio (select): Chocolate, Morango, Baunilha, etc.
📏 Tamanho (radio buttons): Pequeno, Médio, Grande
📅 Data de entrega (input date, required)
Seção 3 - Informações Adicionais:
📝 Observações especiais (textarea)
💵 Orçamento máximo (input number)

🔸feedback.html
Missão: Coletar a opinião sincera dos clientes sobre diferentes aspectos do negócio.
Campos do Formulário:
👤 Nome (opcional, input text)
📧 Email (opcional, input email)
🍞 Produto/Serviço (select, required): Pães, doces, salgagos, atendimento...
🔵Avaliação Geral (radio buttons, required): Excelente, bom, ruim...

🔸cadastro.html
Missão: Construir um formulário completo para registrar novos clientes, coletando dados diversos e obtendo consentimentos.
Seção 1 - Dados Pessoais:
👤 Nome completo (required)
📧 Email (required, tipo email)
📞 Telefone (required, com pattern)
🎂 Data de nascimento (input date)
Seção 2 - Endereço:
🏠 Rua (required)
🔢 Número (required, tipo number)
🏘️ Bairro (required)
📮 CEP (required, pattern="[0-9]{5}-[0-9]{3}")
Seção 3 - Preferências:
📌Tipos de produtos favoritos (checkboxes múltiplos):
Seção 4 - Termos:
📩 Aceita receber promoções por email (checkbox required)
✅ Aceita os termos de uso (checkbox required)

✅✅Desenvolvimento e estrutura do projeto:  <br>
🔸index.html  <br>

✅✅ Tags utilizadas:  <br>
➡️ DOCTYPE: <br>
Objetivo: Define o tipo de Documento. <br>
<img height="34" alt="image" src=images/DOCTYPE.png/> <br>
<br>
➡️ HTML: <br>
Objetivo: Inicia o código e definindo o idioma. <br>
<img height="34" alt="image" src=images/HTML.png/> <br>
<br>
➡️ HEAD: <br>
Objetivo: Cabeçalho do site. <br>
<img height="34" alt="image" src=images/HEAD.png/> <br>
<br>
➡️ BODY: <br>
Objetivo: Corpo do site. <br>
<img height="34" alt="image" src=images/BODY.png/> <br>
<br>
➡️ TITLE: <br>
Objetivo: Titulo do site, ou seja, é o nome que aparece na aba do navegado. <br>
<img height="34" alt="image" src=images/TITLE.png/>  <br>
<br>
➡️ H1, H2, H3, H4: <br>
Objetivo: Titulo Principal. <br>
Tem vários tamanhos: h1, h2, h3 e h4. <br>
Quanto maior o número, menor o texto. <br>
<img height="34" alt="image" src=images/H1.png/> <br>
<br>
➡️ P: <br>
Objetivo: Parágrafo. <br>
<img height="34" alt="image" src=images/P.png/>  <br>
<br>
➡️ NAV: <br>
Objetivo: A tag nav é utilizada para barra de navegação, gerando link para mudar de página ou direcionar o usuário para outro local do site. <br>
<img alt="image" src=images/NAV.png/> <br>
<br>
➡️ SELECTION: <br>
Objetivo: Quando o dev deseja direcionar o usuário dentro da mesma página, deve usar a tag section e o id. <br>
Ao usuário clicar no link, ele será direcionado para esse selection que possui o mesmo id do link. <br>
<img alt="image" src=images/SELECTION.png/> <br>
<br>
➡️ LI: <br>
Objetivo: Aqui estou utilizando a tag li que faz a listagem dos itens. <br>
E para testar dois tipos de visuais, utilizei a tag ol e a tag ul. <br>
<img alt="image" src=images/LI.png/> <br>
<br>
➡️ OL: <br>
Objetivo: A lista que utiliza a tag ol, lista os itens em ordem numérica. <br>
Ou seja: a primeira tag li aparece com o pré-fixo 1. <br>
<img width="300" alt="image" src=images/OL.png/>  <br>
<br>
➡️ UL: <br>
Objetivo: A lista que utiliza a tag ul, lista todos os itens com um marcador circular ("bolinha") no pré-fixo. <br>
<img width="400" alt="image" src=images/UL.png/>  <br>
<br>
➡️ FOOTER: <br>
Objetivo: Define rodapé. <br>
Esse elemento fica dentro do body. <br>
<img height="34" alt="image" src=images/FOOTER.png/> <br>
<br>
➡️ TABLE: <br>
Objetivo: Criar uma tabela. <br>
<img width="500" alt="image" src=images/TABLE-visual.png/> <br>
➡︎ Para criar a estrutura da tabela, devemos utilizar a tag table. <br>
Dentro dessa tag, vamos colocar mais duas tag: thead e tbody. <br>
➡︎ A tag thead é utilizada para definir o cabeçalho. Ou seja, é a primeira linha. <br>
Dentro da tag thead precisa ter a estrutura tr e th. <br>
➡︎ A tag tbody é utilizada para inserir as informações na tabela, é o corpo da tabela. <br>
Dentro da tag tbody precisa ter a estrutura tr e td. <br>
<img width="400" alt="image" src=images/TABLE-estrutura.png/> <br>
<br>

✅✅ Resultado: <br>
Link da página: https://marianavagula.github.io/FAT-WEB-PRATICA-3/  
<br>







