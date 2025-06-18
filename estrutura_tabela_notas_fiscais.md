# Estrutura da Tabela `notas_fiscais`

```sql
CREATE TABLE notas_fiscais (
  chave_acesso text,
  modelo text,
  serie text,
  numero text,
  natureza_operacao text,
  data_emissao date DEFAULT NULL,
  razao_social_emitente text,
  inscricao_estadual_emitente text,
  uf_emitente text,
  municipio_emitente text,
  cnpj_destinatario text,
  nome_destinatario text,
  uf_destinatario text,
  indicador_ie_destinatario text,
  destino_operacao text,
  consumidor_final text,
  presenca_comprador text,
  numero_produto text,
  descricao_produto_servico text,
  codigo_ncm text,
  tipo_produto text,
  cfop text,
  quantidade decimal(10,2) DEFAULT NULL,
  unidade text,
  valor_unitario decimal(10,2) DEFAULT NULL,
  valor_total decimal(10,2) DEFAULT NULL,
  evento_mais_recente text,
  data_evento_mais_recente text,
  valor_nota_fiscal decimal(10,2) DEFAULT NULL,
  notas_fiscaiscol text,
  cpf_cnpj_emitente text,
  notas_fiscaiscol1 varchar(45) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;
```
# Abaixo está a imagem representando o fluxo completo do agente:

![Fluxo do Agente](/agente-img/N8N-AGENTE.jpeg)