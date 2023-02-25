# Diagrama de Oficina Mecânica

- Um cliente pode levar um ou vários veículos a uma Oficina Mêcanica, logo o relacionamento de cliente para veículo é de um para vários, e do veículo à Oficina é de vários para um, o véiculo usufrui a foreign key de IdClient e idWorkshop.
- Uma Oficina Mecânica pode ter um ou vários mecânicos e, portanto, um ou vários mecânicos podem constituir uma equipe. Logo, as foreign key de idWorkshop e idTeam estão em Mecânicos.
- Uma equipe pode ter um ou vários serviços.
- Uma ordem de serviço pode ter um ou vários serviços e serviços pode ter um várias ordens de serviço, logo o relacionamento é de M para N, fazendo uma relação entre Ordem de serviço/Serviço. Possuindo as foreign key: IdServiceOrder e idService.
- Uma ordem de serviço pode ter um ou várias peças, e peças podem ter um ou várias ordens de serviço, logo o relacionamento também é de M para N, fazendo uma relação entre Ordem de serviço/Peça. Possuindo as foreign key: idServiceOrder e idPart.

### Autor: José Gabriel dos Santos Pádua
