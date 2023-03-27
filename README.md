# Projeto Integrador - B&B Veículos Multimarcas

Documentação para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

Estudantes: [Eduardo Barbaro](github.com/dudubarbaro) e [Brunno Duarte da Cunha](https://github.com/BrunnoDC).

Links do projeto:

-   [Documentação](github.com/dudubarbaro/pi-modelo)
-   [Backend]()
-   [Frontend]()

# Ponto de Vendas (PDV)

Gerenciamento de vendas para uma loja de veículos

  O nossa empresa, B&B Veículos Multimarcas, está crescendo, devido a qualidade de seus produtos. Recentemente, contratamos dois funcionários para o gerenciamento e desenvolvimento digital.
  Assim, atualmente, conseguimos e concentrar nossos esforços para melhorar a gestão da loja. Para isso, queremos adquirir um sistema de controle de vendas que nos permita lançar as vendas realizadas e gerenciar o estoque. Como nossa intenção é melhorar a gestão do negócio, é muito importante que consigamos ter relatórios, como por exemplo, de vendas.

# Situação Problema

  O cliente conhece nossa loja por meio de nossos conteúdos digitais em nossas redes sociais, indicações ou até por propagandas e folhetos impressos. A fim de fazer seu cadastro, com a ideia de comprar, cotar ou apenas verificar um veículo, ele nos contacta e vai até a loja.
  Na loja, ele é bem recepcionado pelos donos, com uma conversa objetiva e clara, nós da B&B Veículos Multimarcas, apresentamos os veículos de interesse do possível comprador, o fidelizamos e partimos para uma reunião de compra em um ambiente mais tranquilo e climatizado para melhor conversação de ideias.
  Com a compra já idealizada pelo cliente, nós oferecemos nossas ofertas de financiamento e seguro, para melhor adesão do comprador preservando sua aquisição. Com a compra finalizada, alguns papéis vinculados aos dados do comprador, do vendedor e do veículo, advindos do financiamento, são assinados e acordados por ambas as partes. O pagamento é negociado e o cliente já tem a liberdade de sair com seu novo veículo!
  Com isso notamos alguns problemas em relação ao gerenciamento dos veículos no estoque/pátio, controle de entrada e saída dos automóveis, controle de clientes e divulgações para vendas em redes sociais, por serem muito fechadas ao seu público alvo nativo. 
  Já atuando na resolução desses problemas, escolhemos por obter o desenvolvimento de um software de gerenciamento e vendas para nos ajudar a manter o maior controle e segurança de nossos produtos e clientes, principalmente, com um domínio próprio na internet, uma maior liberdade de divulgação e modernidade à nossa empresa.

# Descrição da proposta

O desenvolvimento do predicado software advém da necessidade da situação-problema que se caracteriza com a relação ao gerenciamento dos veículos no estoque/pátio, controle de entrada e saída dos automóveis, controle de clientes e divulgações para vendas em redes sociais, por serem muito fechadas ao seu público alvo nativo.
Para isso o sistema terá seu foco no gerenciamento de veículos e clientes. O sistema permitirá a adição e a remoção de veículos, a visualização e controle do estoque, relatório de entrada e saída de veículos e registro da venda ao cliente. Dois níveis de usuário: Admin e Cliente. O Admin terá acesso as telas de gerenciamento, controle, relatório e registro de venda. O usuário Cliente terá acesso a tela de visualização dos veículos disponíveis para compra e tela de finalização de compra.

# Regras de Ngócio

**RN01 - Cadastro de veículos:** Para iniciar uma venda, é de suma importância ter um veículo cadastrado.
**RN02 - Adicionar uma venda:**  Para adicionar um veículo a uma venda, é preciso que o veículo esteja cadastrado no sistema e que seu preço seja acima de zero.
**RN03 - Cadastro de usuários:** Os usuários precisam realizar o cadastro para fazer a compra.
**RN04 - Efetuar compra:** Para realizar a compra, apenas com usuários cadastrados e nenhuma outra compra em aberto.
**RN05 - Registro de compra:** O Administrador deve possuir acesso aos gerenciamentos de compras
**RN06 - Desfazer compra em aberto:** O usuário que possuir compras em aberto deverá desfazer sua pendência.
**RN07 – Impressão da venda:** Com as informações da venda registrada, o adminstrador deve imprimir a venda e enviar ao usuário para aprovação, e caso o usuário aprovar, o administrador deve solicitar a sua assinatura online para aprovar a execução do serviço.
**RN08 – Abertura de OS:** Com a venda aprovada pelo usuário, o administrador deverá receber os dados do usuário e da venda em um novo formulário, para o gerenciamento interno, realizando a abertura da venda.
**RN09 – Gerenciamento de fluxo de vendas:** O gerenciamento de fluxo de venda será permitido somente para o administrador.