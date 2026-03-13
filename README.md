# Consumo de ferramentas

## Como acessar lista de consumo pelo SAP
1. Execute a transação MB51
2. Preencha os seguintes campos:
* Centro: 3110
* Depósito: 1070
* Tipo de movimentao: 201 - 202 (estorno)
* Data de lançamento: 'Data inicial' - 'Data final'
3. No campo 'Opções de exibição'
* Selecione a opção 'Lista plena'
* Preencha o campo 'Layout' com o texto '/MARTY1'
4. Precione botão 'Executar' ou atalho F8

### obs¹.: caso precise inserir ou remover colunas da visualização, precione o botão 'Variante de exibição atual' ou o atalho Ctrl + F8, mova para a caixa 'Colunas exibidas' as colunas a serem exibidas e precione o botão 'Aceitar' ou o atalho Enter

### obs².: para fazer o download da lista em .csv basta abrir o menu 'Lista', o sub-menu 'Exportar' e precione a opção 'Planilha eletrônica'. No campo 'Formato', selecione a opção 'File separado por vírgula (*.csv)' e precione o botão 'Exportar para...' ou o atalho Shift + F8. Selecione o diretório de destino e precione o botão 'Salvar'

### obs³.: o SAP-HANA MSB permitiu a consulta de um período de 4 anos. Consultas com períodos de tempo superiores a esta não foram experimentadas.

---

# Procução

## Como acessar lista de produção pelo SAP
1. Execute a transação ZPP020
2. Preencha os seguintes campos:
* Centro: 3110
* Nº material para ordem (não obrigatório): 'código da peça'
* Data de lançamento: 'Data inicial' - 'Data final'
3. Precione botão 'Executar' ou atalho F8

### obs.: caso precise remover os sub-totais da visualização basta precione o botão 'Subtotais...' ou o atalho Ctrl + Shift + F6, desmarcar as solunas com sub-totais ativos e precione o botão 'Aceitar' ou o atalho Enter

### obs².: para fazer o download da lista em .csv basta abrir o menu 'Lista', o sub-menu 'Exportar' e precione a opção 'Planilha eletrônica'. No campo 'Formato', selecione a opção 'File separado por vírgula (*.csv)' e precione o botão 'Exportar para...' ou o atalho Shift + F8. Selecione o diretório de destino e precione o botão 'Salvar'

### obs³.: no SAP-HANA MSB o limite para consulta de produção é de aproximadamente 2 meses. Períodos de tempos maiores são interrompidos e a consulta não é mostrada.