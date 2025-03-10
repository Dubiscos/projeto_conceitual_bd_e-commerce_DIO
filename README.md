# Projeto de Refinamento Conceitual de Banco de Dados E-COMMERCE:

#### Projeto proposto no Bootcamp [Heineken - Inteligência Artificial Aplicada a Dados com Copilot](https://web.dio.me/track/coding-the-future-heineken-ia-para-analise-de-dados) na plataforma [DIO.](https://www.dio.me/)

### Descrição do Desafio
_"Modelamos juntos um contexto reduzido de e-commerce. Agora é a sua vez, podes escolher a ferramenta de modelagem para realizar o desafio. Contudo, fique atento! Caso opte por uma variação do modelo entidade relacionamento, como nas ferramentas Mysql Workbench ou DBDesigner será preciso especificar as PK e FKs corretamente. Apesar desse conceito não ser utilizado na modelagem conceitual exploramos brevemente suas definições. Sendo assim, seu empregável será o esquema conceitual para o cenário de E-commerce."_ 

Instrutora: *Juliana Mascarenhas*
</b>

### Objetivo:
Refine o modelo apresentado acrescentando os seguintes pontos:

- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
- Entrega – Possui status e código de rastreio;



## Ferramentas utilizadas

- [MySQL Workbench](https://www.mysql.com/products/workbench/)



## Respostas do Desafio

![img](https://github.com/Dubiscos/projeto_conceitual_bd_e-commerce_DIO/blob/main/Model/Projeto%20conceitual%20e-commerce.png)

- Para a entidade Cliente foram criadas duas novas entidades  ``PessoaJuridica`` e ``PessoaFisica`` contendo as informações de CNPJ e CPF.
- No caso de Pagamento a entidade esta atribuída a outras três entidades afim de detalhar as formas de pagamento : Cartão, Boleto e Pix.
- Entrega foi criada para armazenar as informações de envio de cada pedido detalhar como data do pedido, data de envio e data de entrega.
