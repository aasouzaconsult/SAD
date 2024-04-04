# Exemplo 1 - Vendas

## Criando a tabela
```sql
CREATE TABLE Vendas (
    VendaID INT IDENTITY(1,1) PRIMARY KEY,
    DataVenda DATETIME,
    ValorVenda DECIMAL(10, 2),
    ClienteID INT,
    NomeCliente NVARCHAR(100),
    EnderecoCliente NVARCHAR(255),
    ProdutoID INT,
    NomeProduto NVARCHAR(100),
    PrecoUnitario DECIMAL(10, 2),
    Quantidade INT,
    VendedorID INT,
    NomeVendedor NVARCHAR(100)
);
```
## Inserindo dados
```sql
DECLARE @i INT = 0;

WHILE @i < 200
BEGIN
    INSERT INTO Vendas (
        DataVenda,
        ValorVenda,
        ClienteID,
        NomeCliente,
        EnderecoCliente,
        ProdutoID,
        NomeProduto,
        PrecoUnitario,
        Quantidade,
        VendedorID,
        NomeVendedor
    )
    VALUES (
        GETDATE(),
        ROUND((RAND() * (500 - 50) + 50), 2),
        @i % 10 + 1,
        'Cliente ' + CAST((@i % 10 + 1) AS NVARCHAR(10)),
        'Endereço ' + CAST((@i % 10 + 1) AS NVARCHAR(10)),
        @i % 5 + 1,
        'Produto ' + CAST((@i % 5 + 1) AS NVARCHAR(10)),
        ROUND((RAND() * (100 - 10) + 10), 2),
        @i % 3 + 1,
        @i % 4 + 1,
        'Vendedor ' + CAST((@i % 4 + 1) AS NVARCHAR(10))
    );

    SET @i = @i + 1;
END
```
## Consultando

```sql
SELECT * FROM Vendas;
```

## Criar o Data Warehouse
ODS, Tabela Fato e Dimensões!
Não se esqueça da tabela dimensão de data!


