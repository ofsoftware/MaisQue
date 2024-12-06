# Remover Produto do Catalogo do Serviço

**COMO** usuário autorizado do serviço,  
**QUERO** remover produtos cadastrados no serviço, retirando, logicamente, dos produtos que o contratante poderá disponibilizar    
**PARA** excluir itens descontinuados ou que não são mais relevantes para o serviço ofertado.

---

### Critérios de Aceitação:

1. O sistema deve permitir:
   - Localizar um produto existente por **Nome** ou **Status**.
   - Confirmar a remoção do produto antes de realizar a exclusão definitiva.

2. Após a exclusão:
   - O produto deve ser removido da lista de produtos disponíveis.
   - O sistema deve registrar a exclusão com data, hora e o responsável pela ação.

3. O sistema deve:
   - Exibir uma mensagem de confirmação após a exclusão bem-sucedida.
   - Exibir um alerta caso o produto não seja encontrado ou não possa ser removido.


---

### Considerações Técnicas (Aplicáveis a Todas as Operações):
- O sistema deve garantir que todas as ações realizadas sejam registradas para fins de auditoria.
- Operações devem ser seguras e acessíveis apenas para usuários com permissões adequadas.
