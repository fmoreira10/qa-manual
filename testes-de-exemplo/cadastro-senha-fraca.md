# Caso de Teste: Cadastro com Senha Fraca

- **ID**: CT-004  
- **Módulo**: Cadastro  
- **Título**: Validar requisito de senha segura  
- **Pré-condições**: Página de cadastro acessível  

- **Passos para execução**:  
  1. Acessar a página de cadastro  
  2. Preencher todos os campos corretamente  
  3. Preencher o campo "Senha" com o valor: `123` (senha curta e fraca)  
  4. Preencher o campo "Confirmar Senha" com o mesmo valor  
  5. Clicar no botão "Cadastrar"  

- **Resultado Esperado**:  
  - O sistema deve impedir o cadastro  
  - Exibir mensagem de erro: "Senha deve ter ao menos 8 caracteres"  

- **Resultado Obtido**:  
  - (Para preencher após o teste)
