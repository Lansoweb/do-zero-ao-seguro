# Checklist de Segurança e Resiliência – Gestão de Identidades e Acessos (IAM)

| Tópico                                                                                                              | ✅  |
|----------------------------------------------------------------------------------------------------------------------|-----|
| Todas as identidades (usuários, serviços, máquinas) são gerenciadas de forma centralizada?                          | [ ] |
| O acesso é concedido com base no princípio do menor privilégio?                                                     | [ ] |
| Autenticação multifator (MFA) está habilitada para usuários e administradores?                                      | [ ] |
| Há políticas de expiração e rotação para senhas, tokens e chaves de API?                                            | [ ] |
| Os acessos são registrados e auditados, com alertas para tentativas suspeitas ou falhas repetidas?                  | [ ] |
| Existe um processo claro de revisão periódica de permissões e remoção de acessos obsoletos (offboarding)?           | [ ] |
| Há segregação de funções críticas (ex: desenvolvimento, operação, auditoria)?                                       | [ ] |
| Contas com privilégios elevados possuem monitoramento e controle reforçado?                                         | [ ] |
| Tokens de acesso são gerados com escopo e validade limitada (ex: OAuth2, JWT com claims)?                           | [ ] |
| Serviços automatizados usam autenticação segura baseada em identidade (ex: workload identity, service accounts)?    | [ ] |
