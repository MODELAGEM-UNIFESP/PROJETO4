# PROJETO4
Criação de uma rede no NetLogo


O projeto visa simular uma rede de indivíduos que podem contrair e transmitir uma doença. Cada indivíduo pode assumir 3 estados:
  - Verde: Indica que o indivíduo está saudável;
  - Azul: Indica que o indivíduo contraiu a doença, mas os sintomas ainda não apareceram;
  - Vermelho: Significa que os sintomas já são percebidos no paciente.
  
Variáveis da Interface:
  - initial-outbreak-size: Quantidade inicial que possui a doença (sem sintomas);
  - recovery-chance: Chance de um indivíduo se recuperar, dado que os sintomas já estão presentes;
  - symptoms-show-max-time: Tempo máximo (em ticks) para que os sintomas apareçam, à partir do ponto em que um indivíduo contrai a doença;
  - factor: Fator que determina se a probabilidade de um indivíduo saudável ficar doente aumenta ou não de acordo com a quantidade de indivíduos com sintomas na sua vizinhança (EX: um indivíduo está saudável, e sua vizinhança consiste em dois indivíduos. Se ambos estiverem com sintomas e factor = 1, então o indivíduo terá uma chance de 100% de ficar doente e sem sintomas. Se um tiver sintomas e o outro não e factor = 1, então o indivíduo terá uma chance de 50% de ficar doente e sem sintomas)
