# Documentação Hackaton
### Requisitos Funcionais e Regra de Negócio
**RF01:** O sistema deve manter os dados de Pessoas. <br>
**RN01:** O sistema deve manter os seguintes dados de pessoas: CPF, data de nascimento e gênero.

**RF02:** O sistema deve manter os dados do cliente. <br>
**RN02:** O sistema deve manter os dados do cliente como: nome, e-mail, telefone.
**RN03:** O sistema deve manter os dados do cliente se é uma pessoa jurídica, com CNPJ e nome fantasia.

**RF03:** O sistema deve manter os dados de endereço. <br>
**RN04:** O sistema deve manter os dados de endereço como CEP, cidade, estado, bairro, endereço e complemento da localização.<br>

**RF04:** O sistema deve manter os dados do motorista.<br>
**RN05:** O sistema deve manter os dados do motorista como: nome, e-mail, senha, CEP, cidade, estado, bairro, endereço, complemento da localização, telefone, categoria da carteira, CNH.

**RF05:** O sistema deve manter os dados funcionário.<br>
**RN06:** O sistema deve manter os dados do funcionário como: nome, e-mail, senha, CEP, cidade, estado, bairro, endereço, complemento da localização, telefone, verificar se é administrador.<br>
**RN07:** O sistema deve manter os cargos do funcionário junto com a data de admissão e a data de demissão.

**RF06:** O sistema deve manter os dados dos veículos.<br>
**RN08:** O sistema deve manter os dados dos veículos como: placa, modelo, número de eixos, se pertence a alguma empresa, tipo de veículo, status e marca.

**RF07:** O sistema deve manter marcas. <br>
**RN09:** O sistema deve manter nome das marcas atribuidas.<br>

**RF08:** O sistema deve manter os dados dos itens pedidos.<br>
**RN10:** O sistema deve manter os dados dos itens pedidos como: nome do item, quantidade, peso, altura e uma observação sobre o item e os dados do pedido.

**RF09:** O sistema deve manter os dados da entrega.<br>
**RN11:** O sistema deve manter os dados da entrega como: posição do motorista, data prevista da entrega, data efetiva da entrega, data prevista da coleta, data efetiva da coleta e dados do pedido.<br>
**RN12:** A data prevista para coleta só poderá ser gerada após registrar um motorista neste pedido.<br>
**RN13:** A data efetiva só poderá ser registrada após a entrega ter sido realizada 

**RF10:** O sistema deve manter os dados do pedido.<br>
**RN14:** O sistema deve manter os dados do pedido como: status, data do pedido, dados do pagamento, dados do motorista, dados do cliente, dados do veículo e dados da entrega.<br>
**RN15:** Os dados do motorista e do veículo só serão atribuídos depois do pagamento ser confirmado

**RF11:** O sistema deve manter os dados do endereço da coleta.<br>
**RN16:** O sistema deve manter os dados do endereço da coleta como: CEP, cidade, estado, bairro, endereço, complemento da localização e dados do pedido.

**RF12:** O sistema deve manter os dados do endereço da entrega.<br>
**RN17:** O sistema deve manter os dados do endereço da entrega como: CEP, cidade, estado, bairro, endereço, complemento da localização e dados do pedido.

**RF13:** O sistema deve manter os dados do pagamento.<br>
**RN18:** O sistema deve manter os seguintes dados de pagamento: Status, Valor, Data efetiva do pagamento, data de geração e pix cópia e cola.

**RF14:** O sistema deve manter cargos da empresa.<br>
**RN19:** O sitema deve manter o nome dos cargos.<br>
**RN20:** O sistema deve atribuir os funcionários a seu cargo expecifico.<br>
**RN21:** O sistema deve manter a data de admissão do funcionario.<br>
**RN22:** O sistema deve manter a data de demição do funcionario caso ele seja demitido.<br>

### Requisitos Não Funcionais
**RNF01:** O backend do sistema será feito em Django. <br>
**RNF02:** A modelagem do banco de dados do sistema deve feito em MySQL workbench<br>
**RNF03:** Deve utilizar o Figma como criação do design do site<br>
**RNF04:** Deve utilizar o Vue como framework de frontend<br>
**RNF05:** A plataforma de gerenciamento de projeto deve ser o GitHub<br>
