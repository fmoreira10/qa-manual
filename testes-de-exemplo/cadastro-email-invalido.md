# Caso de Teste: Cadastro com E-mail Inválido

- **ID**: CT-003  
- **Módulo**: Cadastro  
- **Título**: Validar campo e-mail com formato inválido  
- **Pré-condições**: Página de cadastro acessível  

- **Passos para execução**:  
  1. Acessar a página de cadastro  
  2. Preencher o campo "Nome Completo" com um nome válido  
  3. Preencher o campo "E-mail" com o valor: `usuario@invalido`  
  4. Preencher os demais campos obrigatórios corretamente  
  5. Clicar no botão "Cadastrar"  

- **Resultado Esperado**:  
  - O sistema deve impedir o cadastro  
  - Deve exibir mensagem de erro: "E-mail inválido" próxima ao campo e-mail  

- **Resultado Obtido**:  
  - (Para preencher após o teste)
