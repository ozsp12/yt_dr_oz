# Sistema dinâmico do pêndulo duplo

O pêndulo duplo é um sistema mecânico não linear clássico no qual equações determinísticas podem produzir trajetórias com forte divergência sob pequenas perturbações nas condições iniciais. O notebook deduz as equações pelo formalismo de Euler–Lagrange, integra numericamente o sistema acoplado e anima o movimento resultante.

## Material

- `double_pendulum_dynamical_system.ipynb`: modelo, equações, procedimento numérico e visualização.
- `double_pendulum_chaos.gif` e `double_pendulum_chaos.mp4`: animações renderizadas das trajetórias.

A simulação ilustra a sensibilidade às condições iniciais; por si só, não estima expoentes de Lyapunov nem demonstra a existência de dinâmica caótica. Seu uso em pesquisa exigiria testes de tolerância do integrador, análise de convergência, inspeção da deriva de energia e comparação com um integrador que preserve a estrutura do sistema.

[Voltar à organização do repositório](../../README.md#organização-do-repositório).
