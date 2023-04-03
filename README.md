<!-- # H1
1. Lista
# H2
**Negrito**
- Tópicos -->

# Projeto Integrador - Larissa e Vinicius

Desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

Alunos: [Larissa Cristina Bileski](github.com/larissabileski) e [Vinicius Henrique da Silva](github.com/viniihds). 

Professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Links do projeto:

-   [Documentação (esse documento)]()
-   [Backend]()
-   [Frontend]()

<!-- # Modelos de Sistemas

## 1- Ponto de Vendas (PDV)

**Gerenciamento de vendas para uma padaria**

O nosso cliente, Sr. Genival, tem uma padaria de bairro chamada padaria Pão Genial e, devido a qualidade de seus produtos, ela está crescendo rapidamente. Recentemente, ele contratou mais funcionários para atendimento, caixa, panificação, etc.
Assim, atualmente, ele consegue concentrar seus esforços para melhorar a gestão da padaria. Para isso, ele quer instalar um sistema de controle de vendas que permita ao caixa lançar as vendas realizadas. Como sua intenção
é melhorar a gestão do negócio, é muito importante que ele consiga ter
relatórios, como por exemplo, de vendas.-->

# Situação Problema

-   **Introdução**: O sistema será desenvolvido para a empresa Fiberblu. Presente há 28 anos no mercado, é o maior comercio de tanques de fibra na região Sul do país. O dono Odair, o gerente comercial Ednilson, a diretora financeira, e os representantes da empresa, são os principais funcionários e os que terão acesso ao sistema.
-   **Situação-problema**: Atualmente a empresa funciona da seguinte forma: o representante anota o pedido em uma planilha, em seguida, o pedido é enviado por email e depois cadastrado no sistema. O sistema realiza o relatório do pedido e avisa a equipe de estoque. No dia do carregamento, o sistema fatura o pedido, desconta do estoque e é emitido o boleto. Atualmente, no sistema utilizado não há como fazer o pedido direto no sistema, além disso, o sistema também não emite o boleto diretamente para o cliente, nem avisa se o boleto está vencendo ou se foi pago.
-   **Conclusão**: Notamos a falta de alguns recursos no atual software utilizado pela empresa, como por exemplo: O sistema não envia nem notifica o cliente em relação ao boleto, seja para avisar sobre o prazo do pagamento ou eventual vencimento. Outra dificuldade que percebemos foi que, o sistema não tem uma opção para fazer pedidos. O cliente faz o pedido por uma planilha, envia por e-mail, e os administradores do sistema precisam registrar o pedido.

# Descrição da proposta

**Alguns pontos importantes a se destacar são:**

-   **Qual o foco de ação do software** : Acessar o relatório de vendas, controle de estoque, gerir ganhos e despesas, gerenciar cota de representantes, emissão de boletos após o faturamento dos pedidos e mensagens automáticas.
-   **Os níveis de usuário do sistema**: O acesso ao sistema será restrito ao dono, ao gerente comercial, ao diretor financeiro e aos representantes da empresa. O dono terá acesso a, o gerente comercial terá acesso a, o diretor fincanceiro terá acesso ao relatório e histórico de vendas, ao gerenciamento de ganhos e despesas e as emissões de boletos, e os representantes terão acesso ao estoque e aos pedidos efetuados no sistema.
-   **O que poderá ser feito no software**: O software será utilizado para: acessar relatório e histórico de vendas, controle de estoque, gerir ganhos e despesas, gerenciar cota de representantes, emissão de boletos após o faturamento dos pedidos, mensagens automáticas após algumas ações( faturamento, emissões de boletos, vencimento de boletos ).
-   # Regras de negócio

- **RN01** – Requisito do Cliente: Apenas pessoas jurídicas podem efetuar pedidos.

<!-- **Nessa parte a equipe deve descrever as regras de negócio que serão implementadas no sistema. O texto abaixo descreve o que essa etapa deve conter e pode ser apagado depois.**

As **Regras de negócio** são orientações e restrições que ajudam a regular as operações de uma empresa. **Regras** foram criadas para **colaborar com o funcionamento**, seja da sociedade, de uma escola, de um jogo, etc. Não seria diferente nas organizações. Vamos abordar melhor sobre esse assunto. Entender o que são as
regras de negócio, sua importância, como são aplicadas e
automatizadas na gestão por processo.

## 4.1 O que são regras de negócio?

Um negócio funciona por processos que, por sua vez, são formados por atividades relacionadas entre si.

As funções das áreas de compras, estoque, logística, finanças, vendas e marketing, por exemplo, compõem um processo de fornecimento de um produto ao cliente.

Dentro desses processos, existem regras que devem ser seguidas durante a execução das atividades, que ajudam a definir **COMO** as operações devem ser realizadas e gerenciadas, **POR QUEM**, **QUANDO**, **ONDE** e **POR QUÊ**.

Podemos dizer que as regras de negócio são **limites impostos às operações**, de forma que elas sigam corretamente em direção às políticas e aos objetivos da instituição.

## 4.2 Regras para a criação de regras de negócio

De maneira geral, as regras de negócio devem:
- Ser **simples**, isto é,  ter apenas uma função.
- Ser **completas**, com início, meio e fim.
- Ser possíveis de **mensurar** e **rastrear**.
- Estar em consonância com a **legislação**.
- Estar **atualizadas** e sempre **revisadas**.
- Refletir a **política** e os **valores** da organização.
- Ser **inteligíveis** para os colaboradores e envolvidos no processo.

## 4.3 Por que ter regras de negócio?

- **Padronização de processos:** padronizam os processos e auxiliam a fluirem de forma mais eficiente e automatizada.
- **Controle de processos:** auxiliam no controle de processos, pois falhas são identificadas e corrigidas mais rapidamente.
- **Tomada de decisão:** auxiliam na tomada de decisão e no cumprimento de estratégias pré-estabelecidas.

## 4.4 Exemplos de regras de negócio

- Em um controle de qualidade de granja, pode-se dizer que a cada 100 ovos impróprios para consumo, o lote será descartado.
- Em um banco, clientes com faturamento mensal de mais de R$ 25 mil e CPF sem restrições, serão atendidos pelo gerente Premium pessoa física.
- Para conclusão de licitações, devem ser feitos três orçamentos e o vencedor será sempre o de menor preço final.
- Em um processo de seleção de RH, o candidato só pode ser aprovado se tiver mais de 5 anos de experiência na área, diploma de pós-graduação, espanhol fluente e pretensão salarial abaixo de R$ 8.000,00.
- Em um processo de vendas, o vendedor só pode vender um produto se o cliente tiver mais de 18 anos, renda familiar acima de R$ 5.000,00 e não tiver restrições no CPF.
- Em um processo de compras, o fornecedor só pode ser contratado se tiver nota fiscal, certificado de qualidade e preço abaixo de R$ 10,00 por unidade.
- Em um processo de logística, o pedido só pode ser enviado se o cliente tiver mais de 18 anos, endereço de entrega no mesmo estado e não tiver restrições no CPF.

## 4.5 Como escrever regras de negócio?

- Número identificador.
- Nome da regra.
- Data de criação e data da última alteração para comparações e
controle.
- Nome dos Autores das versões.
- Número da versão (1, 2 etc).
- Dependências: insira o identificador das regras atreladas, às quais a regra em questão depende.
- Uma descrição detalhada para compreensão da regra.

## 4.6 Exemplos de regras de negócio com formatação

- **RN01 – Criação Comanda:** Para iniciar um atendimento no balcão, é necessário primeiro abrir uma nova comanda.
- **RN02 – Inserir Produtos Comanda:** Para inserir um produto na comanda, é necessário que o produto esteja cadastrado no sistema e que a quantia comprada seja acima de zero.
- **RN03 – Cadastro de Leitores:** Os leitores precisam fazer o cadastro para realizar o empréstimo.
- **RN04 – Realizar Empréstimo:** Para realizar o empréstimo, apenas leitores com cadastro e nenhuma multa em aberto.
- **RN05 – Registro de Empréstimo:** O gerente deve possuir acesso aos registros de empréstimos.
- **RN06 – Pagamento de Multa:** O leitor que passar de 15 dias com o livro deverá pagar a multa de um real por dia de atraso.
- **RN07 – Impressão de Orçamento:** Com as informações do
orçamento registradas, a atendente deve imprimir o orçamento e
repassar ao cliente para aprovação, e caso o cliente aprovar, a atendente deve solicitar a sua assinatura para aprovar a execução do serviço.
- **RN08 – Abertura de OS:** Com o atendimento aprovado pelo cliente, a atendente deverá inserir os dados do cliente e do orçamento em um novo documento, para registros internos, realizando a abertura da OS.
- **RN09 – Relatório de Fluxo de Caixa:** O relatório de fluxo de caixa será permitido somente para o administrador. -->
