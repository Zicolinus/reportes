
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
    - Nível Remuneratório -> código do último nível remuneratório do trabalhador (relevante)
    - Habilitação -> código do nível de habilitação mais alto do trabalhador (relevante)
    - TipoContrato -> código do tipo de vínculo contratual do trabalhador com a Lisboa SRU (relevante)
    - Sexo (relevante)


## Tabela historico

Colunas:
    - Funcionário -> número mecanográfico dos trabalhadores; em formato texto, ###; pode ser transformado em formato número inteiro (relevante)
    - Nome -> nome completo dos trabalhadores (relevante)
    - DataInicio -> data de início do período do trabalhador naquele nível remuneratório (relevante)
    - DataFim -> data de fim do período do trabalhador naquele nível remuneratório (relevante)
    - Carreira -> código da carreira do trabalhador (relevante)
    - DescCarreira -> carreira do trabalhador (relevante)
    - Categoria -> código da categoria do trabalhador (relevante)
    - DescCategoria -> categoria do trabalhador (relevante)
    - Nivel -> código do nível remuneratório (relevante)
    - DescrNivel -> descrição do nível remuneratório (relevante)
    - ValorNivel -> valor da remuneração correspondente ao nível (relevante)


## Tabela niveis_remuneratorios

Colunas:
    - Nível -> código do nível remuneratório (relevante)
    - Descrição -> primeira parte da descrição do nível remuneratório (relevante)
    - Transição -> não sei o que é
    - Nível Transição -> não sei o que é
    - Indice -> não sei o que é
    - Valor -> valor remuneratório correspondente ao nível e ao ano identificado na data na coluna 'Datainicial' (relevante)
    - DataInicial -> data em que o trabalhador passou a estar integrado naquele nível remuneratório (relevante)


## Tabela processamento_####

Colunas:
    - Ano (relevante)
    - Mes (relevante)
    - Funcionario -> número mecanográfico dos trabalhadores; em formato texto, ###; pode ser transformado em formato número inteiro (relevante)
    - Nome -> nome completo dos trabalhadores (relevante)
    - OrgaoSocial -> não sei o que é
    - Contribuinte -> número de contribuinte do trabalhador
    - NumSSocial -> número de segurança social do trabalhador
    - NumCGA -> número da Caixa Geral de Aposentações do trabalhador
    - Departamento -> Unidade Orgânica (relevante)
    - TipoPessoalProc -> tipo de vínculo contratual (relevante)
    - TipoProc -> tipo de processamento (relevante)
    - CodMov -> código do movimento (relevante)
    - Descrição -> descrição do movimento (relevante)
    - Valor -> valor dos movimentos a receber ou devidos pelo trabalhador (é negativo se for um desconto do vencimento) (relevante)
    - ValorEncargos -> valor pago pela empresa como encargo sobre o trabalhador (relevante)
    - ValorMapaSS -> soma dos valores pagos à Segurança Social (corresponde à soma dos valores, para cada trabalhador em cada mês, em 'Valor' e 'ValorEncargos' dos movimentos com descrição 'Segurança Social') (relevante)
    - ValorSujeitoIRS -> valores, dos valores na coluna 'Valor', que estão sujeitos ao cálculo dos descontos de IRS (relevante)
    - ValorDescontadoFaltas -> valores descontados do subsídio devido a absentismo (relevante)
    - ContaCBL -> não sei o que é
    - CCusto -> não sei o que é
    - Organica -> não sei o que é
    - Fonte -> não sei o que é
    - Atividade -> não sei o que é
    - ProgMedida -> não sei o que é
    - Economica -> não sei o que é
    - Diario -> não sei o que é
    - NumDiario -> não sei o que é


## Tabela lista_formacoes

Colunas:
    - PlanoFormacao -> código do plano de formação
    - Curso -> código da formação
    - Descricao -> título da formação
    - TipoAccao -> não sei o que é
    - Obrigatorio -> se é uma formação obrigatória ou não
    - ProcedimentoContratacao -> código interno do procedimento de contratação
    - EstadoCurso -> não sei o que é
    - DisponivelOMNIA -> não sei o que é
    - TotalHoras -> número de horas da formação
    - EntidadeFormadora -> entidade formadora
    - DataLimiteInscricao -> data limite para os trabalhadores se inscreverem
    - Ocorrencia -> 
    - DataInicio -> 
    - DataFim
    - NrInscritos
    - Custo


## Tabela formacoes

Colunas:
    - CodDepartamento
    - DescDepartamento
    - Codigo
    - Nome
    - DataSaida
    - ProcedimentoContratacao
    - CodCurso
    - DescCurso
    - NIFEntidadeFormadora
    - EntidadeFormadora
    - DataInicio
    - DataFim
    - AnoConclusao
    - Horas
    - Custo
    - Estado
    - Motivo
    - PlanoFormacao





# Dashboards e relatórios a produzir

## Trabalhadores e trabalhadoras da Lisboa SRU




## Formação



## Horários de trabalho e absentismo



## Mobilidade






