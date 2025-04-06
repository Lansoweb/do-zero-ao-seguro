# Checklist de Segurança e Resiliência – Implantação e Produção Segura

| Tópico                                                                                                      | ✅  |
|--------------------------------------------------------------------------------------------------------------|-----|
| O pipeline de CI/CD possui etapas de validação de segurança automatizadas?                                  | [ ] |
| As imagens de containers são assinadas, verificadas e baseadas em imagens oficiais/minimalistas?            | [ ] |
| Segredos (chaves, tokens, senhas) são injetados de forma segura, fora do versionamento?                     | [ ] |
| Há segregação de ambientes (dev, staging, produção) com regras de acesso distintas?                         | [ ] |
| Há validação e revisão de permissões em serviços cloud antes do deploy?                                     | [ ] |
| Aplicações em produção são protegidas com WAF, TLS e headers de segurança adequados?                        | [ ] |
| Backups são realizados, criptografados e testados regularmente?                                             | [ ] |
| O rollback está previsto e testado em caso de falha de deploy?                                              | [ ] |
| Logs de produção são coletados de forma segura, com acesso restrito?                                        | [ ] |
| Todo acesso à infraestrutura de produção é autenticado, auditado e com privilégio mínimo?                   | [ ] |
