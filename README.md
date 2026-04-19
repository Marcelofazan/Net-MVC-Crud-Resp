# CRUD-AspNet-MVC-Responsivo-MySQL

Exemplo de utilização do AdminLte com criação de formulário de Usuário e Registro da Conta em MVC com banco de dados MySQL acessando por dicionário de dados, utilizando AdminLTE

* Template Responsivo AdminLTE 3.2 - rc

## Disponivel em (https://adminlte.io/ )

  - [AdminLTE](https://github.com/ColorlibHQ/AdminLTE/archive/refs/tags/v3.2.0-rc.zip)

## Requisitos

Baixar Pacote de Distribuição de Download da biblioteca e descompactar

Criar uma nova pasta chamada adminlte no Solution ERPSimples
- Na Pasta AdminLTE-3.2.0-rc /dist -> Copiar as pastas css, img e js e Colar dentro da pasta adminlte
- Na Pasta AdminLTE-3.2.0-rc /plugins -> Copiar a pasta plugins e Colar dentro da pasta adminlte

Outra forma: 
- Criar uma nova pasta chamada adminlte dentro da pasta /dist no pacote de distribuição 
- Copiar as pastas img / css / js / plugins
- Colar as pastas img / css / js / plugins dentro de adminlte
- Arrastar a pasta adminlte pelo Explorer em cima de Solution ERPSimples e todas pastas criaram automático.

# O que você vai encontrar neste projeto

- **AdminLTE** - Layout Responsivo JavaScript e uso de bibliotecas (Plugins). 
- **Dicionário de Dados** - Contexto definido realizado manualmente com T-SQL.
- **DataTable** - Tabelas de dados em formato Bootstrap .

## Execução da aplicação

Para executar a aplicação é necessário a execução do Script do MySql. 

## String de conexão do banco

Modifique a string de conexão no arquivo **Web.config**, no trecho indicado:

```bash
...
		server=127.0.0.1;userid=root;password=SUASENHA;database=SEUBANCO;persistsecurityinfo=True;
...

```

O script para criação da tabela do exemplo encontra-se na pasta **Database**.

### Aqui está uma demonstração do projeto:

<img width="1339" height="612" alt="CRUD-AspNet-1-N-AdminLTE" src="https://github.com/user-attachments/assets/5e51fc89-102f-4532-8472-ee729953bac1" />

