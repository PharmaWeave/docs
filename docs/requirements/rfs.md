# Requisitos

## Requisitos Funcionais

ID     | Nomenclatura                 | Descrição
------ | ---------------------------- | ---------------------------------------------------------------------------
RF01   | Gestão de redes              | Permitir que o Administrador gerencie redes de farmácias, incluindo cadastro e atualização.
RF02   | Gestão de unidades           | Permitir que o Administrador gerencie unidades, incluindo cadastro, atualização e desativação.
RF03   | Gestão de gerentes           | Permitir que o Administrador cadastre, atualize e desative gerentes das unidades.
RF04   | Gestão de funcionários       | Permitir que Administradores e Gerentes cadastrem, atualizem, desativem e visualizem funcionários.
RF05   | Gestão de produtos           | Permitir que Gerentes e Funcionários cadastrem, atualizem e visualizem produtos, incluindo controle de estoque.
RF06   | Gestão de clientes           | Permitir que Gerentes e Funcionários cadastrem, atualizem e consultem histórico de clientes.
RF07   | Gestão de vendas             | Permitir que Gerentes e Funcionários registrem, atualizem e revertam vendas, integrando com estoque e histórico de clientes.
RF08   | Gestão de promoções          | Permitir que o Gerente crie e atualize promoções associadas a produtos.
RF09   | Notificações automáticas     | O sistema deve enviar automaticamente para os Clientes notificações sobre promoções e atualizações relevantes.

## Requisitos Não Funcionais

ID     | Nomenclatura    | Descrição
------ | --------------- | ---------------------------------------------------------------------------
RNF01  | Usabilidade     | O sistema deve apresentar interface intuitiva, ou seja, ter no máximo 6 botões em cada tela utilizando-se de ícones reconhecidos, a fim de facilitar o uso e navegação.
RNF02  | Desempenho      | O sistema deve processar operações com tempo de resposta de até 500ms, garantindo fluidez na experiência.
RNF03  | Implementação   | O sistema será desenvolvido em Nuxt.js para front-end e Node.js para back-end, utilizando PostgreSQL como banco de dados.
RNF04  | Segurança       | O sistema deve proteger dados sensíveis utilizando-se de criptografia e garantir backup das informações.
