### Cadastro de Produto Pelo Serviço

**COMO** serviço do sistema,  
**QUERO** cadastrar produtos no sistema com as seguintes informações essenciais: identificador único, nome, descrição e imagem,  
**PARA** garantir que os produtos estejam devidamente registrados e disponíveis para o contratante disponibilizar no seu catálago de vendas.  

---

### Critérios de Aceitação:

1. O sistema deve:
   - Gerar automaticamente um **Identificador Único (ID do Produto)** para cada produto.
   - Exigir o preenchimento obrigatório do campo **Nome do Produto**.
   - Exigir o preenchimento obrigatório do campo **Descrição do Produto**.
   - Oferecer a opção de adicionar uma **Imagem/Foto do Produto** (opcional).

2. Produtos cadastrados devem:
   - Ser exibidos imediatamente na lista de produtos disponíveis no sistema, com a imagem, caso cadastrada.
   - Estar disponíveis para consulta e possíveis edições futuras.

3. O cadastro deve ser validado:
   - Nenhum produto pode ser registrado sem um **Nome**.
   - Caso algum campo obrigatório não seja preenchido, o sistema deve exibir mensagens de erro claras.
   - Para o campo **Imagem**, o sistema deve aceitar formatos padrão de imagem (e.g., JPG, PNG).

4. O sistema deve manter um registro:
   - Da data e hora do cadastro.
   - Status do cadastro (cadastrado, solicitado_analise e aprovado)

---
### Considerações Técnicas:
- O **Identificador Único** será gerado automaticamente e será invisível para o usuário final durante o cadastro.
- O campo **Imagem** serão opcionais, podendo ser preenchidos ou deixados em branco.
- A **Imagem** cadastrada deve ser armazenada de forma otimizada para não prejudicar o desempenho do sistema.
- Mensagens de erro devem ser apresentadas no idioma configurado (BR) pelo cliente e de forma compreensível.
