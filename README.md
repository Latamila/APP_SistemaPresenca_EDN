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

Cores escolhidas para o APP:

#94D2BD
#0A9396

![image](https://github.com/user-attachments/assets/6a581340-cbe3-40b0-b701-36553bfae098)

![image](https://github.com/user-attachments/assets/28571c5a-d7fa-40e9-9b4c-e6377f106877)

![image](https://github.com/user-attachments/assets/013a8756-8613-47a3-8222-8506131fc662)

<H1> REGRAS DE NEGÓCIOS PARA DADOS, VIEWS E ACTIONS </H1>
#ACTIONS

Actions Edit, Delet ficam configuradas como HIDE.

ACTION ADD

![image](https://github.com/user-attachments/assets/62426926-bae7-42db-b724-95012d06cc54)

ACTION CHECKOUT

![image](https://github.com/user-attachments/assets/24fd6f32-9516-43dd-9c9c-c1208caf18df)

#DADOS

Coluna virtual TempoEmSala

![image](https://github.com/user-attachments/assets/5adbf5ee-524e-4652-84dd-581556dcad39)

Email

![image](https://github.com/user-attachments/assets/59b23e46-b7fe-4f0a-8eba-5a067f0e6954)

CodigoInserido

![image](https://github.com/user-attachments/assets/141de76a-1e99-4df3-b08f-d103aacdda65)

CodigoSecreto

![image](https://github.com/user-attachments/assets/2c7dbd65-e7b9-4c6f-bb4e-d3e2a49d70ca)






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

- Aplicativo deve ter na tela de Detalhes, o descritivo sobre cada informação fornecida.
  
![image](https://github.com/user-attachments/assets/2d6970d9-5f50-4cd7-bd39-dc8b96b1e5a8)

* Passou no teste.

  


    
<h1> ENCERRAMENTO </h1>

LIÇÕES APRENDIDAS
---
Deve-se fazer mais testes de usabilidade com usuários in loco, pois o que se enxerga no ambiente de desenvolvimento, às vezes, não representa o comportamento do aplicativo, sendo acessado por várias pessoas ao mesmo tempo, em geografias, dispositivos e variáveis tão diferentes. 

Deve-se fazer pequenas mudanças, no aplicativo, por vez. Testar essa mudança e seguir em frente em vez de, fazer várias mudanças ao mesmo tempo, e ficar sem orientação de qual mudança está influenciando tal mudança de comportamento no aplicativo. 

As cores muito claras (tipo neon) e abertas como verde neon ou claro, amarelo claro, não são amigaveis para os clientes, que até agora testaram. 

Todos os botões devem vir com destaque geométrico, quer seja, esferico ou quadrado, em vez de um ícone livre. 

O aplicativo deve ter descritivo, por exemplo: hora do checkin: 19:10:00, em vez de apenas o horário sem a descrição. 
