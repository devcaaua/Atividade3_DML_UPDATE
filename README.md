# Atividade3_DML_UPDATE

### Instrução 1
```SQL
/* USE vendas_informatica;

UPDATE cliente
SET email = "email@gmail.com.br"
WHERE estado IN ("SP", "RJ");

Esse código não  pode ser exuctado por que na criação da tabela não permite que os email sejam iguais.
*/
```

### Instrução 2
```SQL
USE vendas_informatica; 

UPDATE cliente
SET data_cadastro = "2026-01-01" 
WHERE cidade = "Manaus";
```

### Instrução 3
```SQL
USE vendas_informatica; 

UPDATE cliente
SET nome_cliente = 'Michael Jackson'
WHERE id_cliente  = 10;
```

### Instrução 4
```SQL
USE vendas_informatica;

UPDATE produto
SET nome_produto = 'Notebook Lenovo IdeaPAD 7'
WHERE id_produto  = 1;
```

### Instrução 5
```SQL
USE vendas_informatica;

UPDATE produto
SET preco_unitario = 4999.99
WHERE marca = 'DELL'
AND categoria = 'Notebook';
```

### Instrução 6
```SQL
USE vendas_informatica;

UPDATE venda
SET desconto_percentual = 0.01
WHERE quantidade >= 2;
```
