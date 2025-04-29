# APP_SistemaPresenca_EDN
# EM BREVE DOCUMENTAÇÃO

Este aplicativa tem por objetivo captar a presença dos alunos, em diversas aulas, com checkin, checkout e visualizações de tempo em sala assim como as aulas logadas, ao longo do tempo.

<h1> INICIAÇÃO </h1>

# TERMO DE ABERTURA DO PROJETO 

![image](https://github.com/user-attachments/assets/58d0730d-ac0c-4a0f-b130-362be9b58964)


<h1> PLANEJAMENTO </h1>

Ter botão para registrar presença. 
Ter botão para registrar check-out da sala. 

O botão de registrar presença DEVE APARECER  apenas no  horário estipulado pelo professor.
O botão de registrar presença DEVE SUMIR no  horário estipulado pelo professor, não permitindo que o aluno faça o checkin fora do horário.

O aplicativo deve ter autenticação via Google para facilitar acesso e manter login. 

O aplicativo deve ter tela para registrar presença. 
O aplicativo deve ter tela para fazer check-out. 
O aplicativo deve ter tela para métricas da aula. 

O aplicativo deve capturar os tempos que o usuário fez o checkin, checkout e calcular o tempo que ficou em sala logado. 

O aluno não deve poder fazer mais que um checkin por email. 
O aluno não deve ver o botão de ADD, novamente,  após fazer o checkin.

<h1> EXECUÇÃO </h1>

<h1> MONITORAMENTO </h1>

TESTE DE USABILIDADE COM OBSERVABILIDADE COM 53 USUÁRIOS (28/04)
---
- Captura de checkin, checkout e tempo de tela
![image](https://github.com/user-attachments/assets/a3912324-5971-4611-b136-361990c3bd3e)
* Passou no teste. 

- O Aluno não deve ver o botão após fazer o checkin na aula.
  * Falhou no teste.
 
- A tela de registrar presença só deve aparecer para o usuário no horário estipulado.
  * Passou no teste da tela registrar presença aparecer no horário estipulado, porém o botão ADD ficou disponível na tela principal. Assim os alunos puderam fazer o checkin mais de uma vez, inclusive.
    
<h1> ENCERRAMENTO </h1>

LIÇÕES APRENDIDAS
---
Deve-se fazer mais testes de usabilidade com usuários in loco, pois o que se enxerga no ambiente de desenvolvimento, às vezes, não representa o comportamento do aplicativo, sendo acessado por várias pessoas ao mesmo tempo, em geografias, dispositivos e variáveis tão diferentes. 

Deve-se fazer pequenas mudanças, no aplicativo, por vez. Testar essa mudança e seguir em frente em vez de, fazer várias mudanças ao mesmo tempo, e ficar sem orientação de qual mudança está influenciando tal mudança de comportamento no aplicativo. 

As cores muito claras (tipo neon) e abertas como verde neon ou claro, amarelo claro, não são amigaveis para os clientes, que até agora testaram. 

Todos os botões devem vir com destaque geométrico, quer seja, esferico ou quadrado, em vez de um ícone livre. 

O aplicativo deve ter descritivo, por exemplo: hora do checkin: 19:10:00, em vez de apenas o horário sem a descrição. 
