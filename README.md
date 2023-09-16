# atividade-MER-supermercado
CREATE TABLE supermercado_prod (
  nome varchar (200),
  preco int,
  quant estq int,
  marca varchar (200),
  SAC int,
  nacionalidade varchar (200)
  );
 insert into supermercado_prod VALUES ('queijo','5,00','4 pacotes','qualy','0800-123-4567','brasileira');
insert into supermercado_prod VALUES ('queijo prado','7,80','9 pacotes','REIqueijão','0800-123-4132','brasileira');
insert into supermercado_prod VALUES ('queijo provolone','5,50','3 pacotes','qualy','0800-123-3562','brasileira');
insert into supermercado_prod VALUES ('mussarela','3,00','4 pacotes','quality','0800-123-8473','brasileira');
insert into supermercado_prod VALUES ('queijo gorgonzola','5,00','8 pacotes','qualyfer','0800-123-1324','brasileira');
SELECT * from supermercado_prod 
