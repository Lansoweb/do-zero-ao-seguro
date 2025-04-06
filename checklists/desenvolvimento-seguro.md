# Checklist de Segurança e Resiliência – Desenvolvimento Seguro

| Tópico                                                                                                  | ✅  |
|----------------------------------------------------------------------------------------------------------|-----|
| Boas práticas de codificação segura estão documentadas e aplicadas?                                     | [ ] |
| Todo dado de entrada é validado e sanitizado?                                                           | [ ] |
| Senhas e tokens são armazenados usando hash seguro (ex: bcrypt, argon2)?                                | [ ] |
| Informações sensíveis (chaves, credenciais) estão fora do código-fonte?                                 | [ ] |
| Foram aplicadas práticas de “Security by Design” durante o desenvolvimento?                             | [ ] |
| As bibliotecas e dependências utilizadas são atualizadas e monitoradas quanto a vulnerabilidades?       | [ ] |
| O controle de acesso é implementado no back-end (não apenas no front-end)?                              | [ ] |
| Foram definidos testes específicos para verificar segurança do código?                                  | [ ] |
| Há análise estática e/ou linting de segurança no pipeline de CI?                                        | [ ] |
| O uso de ferramentas de IA no desenvolvimento está sujeito a validações e revisão humana?               | [ ] |
