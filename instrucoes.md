
Criação de dashboards para monitorização de vários aspetos da gestão de pessoas na Lsiboa SRU.

Produção de relatórios da informação tratada e relacionada com as visualizações dos dashboards.


# Tabelas de origem dos dados

As tabelas extraídas do CEGID Primavera estão localizadas na pasta raw_tables, em formato de ficheiros excel.

## Tabela trabalhadores

Colunas:
    - Funcionário -> número mecanográfico dos trabalhadores; em formato texto, ###; pode ser transformado em formato número inteiro (relevante)
    - Nome Abreviado -> forma curta dos nomes dos trabalhadores, mais apropriada para visualização de dados (relevante)
    - DataAdmissao -> data de admissão (relevante)
    - DataDemissao -> data de demissão (relevante)
    - CodDepartamento -> código da última Unidade Orgânica a que o trabalhador esteve afeto (relevante)
    - Nível Remuneratório -> código do último nível remuneratório do trabalhador
    - Habilitação -> código do nível de habilitação mais alto do trabalhador
    - TipoContrato -> código do tipo de vínculo contratual do trabalhador com a Lisboa SRU
    - Sexo (relevante)


## Tabela historico

Colunas:
    - Funcionário -> número mecanográfico dos trabalhadores; em formato texto, ###; pode ser transformado em formato número inteiro
    - Nome -> nome completo dos trabalhadores
    - DataInicio -> data de início do período do trabalhador naquele nível remuneratório
    - DataFim -> data de fim do período do trabalhador naquele nível remuneratório
    - Carreira -> código da carreira do trabalhador
    - DescCarreira -> carreira do trabalhador
    - Categoria -> código da categoria do trabalhador
    - DescCategoria -> categoria do trabalhador
    - Nivel -> código do nível remuneratório
    - DescrNivel -> descrição do nível remuneratório
    - ValorNivel -> valor da remuneração correspondente ao nível


## Tabela niveis_remuneratorios

Colunas:
    - Nível -> código do nível remuneratório
    - Descrição -> primeira parte da descrição do nível remuneratório
    - Transição -> não sei o que é
    - Nível Transição -> não sei o que é
    - Indice -> não sei o que é
    - Valor -> valor remuneratório correspondente ao nível e ao ano identificado na data na coluna 'Datainicial'
    - DataInicial -> data em que o trabalhador passou a estar integrado naquele nível remuneratório



# Dashboards e relatórios a produzir

## Trabalhadores e trabalhadoras da Lisboa SRU



## Formação



## Horários de trabalho e absentismo



## Mobilidade


