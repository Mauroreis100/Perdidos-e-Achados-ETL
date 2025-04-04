# Perdidos-e-Achados-ETL

O Instituto Superior de Transportes e Comunicações (ISUTC) é uma instituição de ensino superior em Moçambique com uma vasta comunidade académica. O campus desta instituição é frequentado por várias pessoas e é bastante recorrente que estas percam ou até esqueçam seus bens em vários locais. Esta ocorrência pode comprometer as actividades do dia-a-dia do estudante, docente ou colaborador da instituição a nível pessoal e académico, como por exemplo ao esquecer bens importantes, como chaves de carro, cadernos e outros bens rotulados valiosos. Como estudantes da instituição desde o ano de 2022, notamos um número crescente de relatos de itens perdidos e/ou achados, no maior meio de comunicação da comunidade estudantil do ISUTC – um grupo na rede social WhatsApp com mais de mil integrantes. Embora este canal de comunicação seja útil, quando ocorre uma divulgação dos itens nem todos têm acesso as mensagens em tempo útil. Dos que têm, nem todos prestam atenção ou chegam realmente a abrir a mensagem. Tendo em conta que no mesmo grupo são tratados diversos assuntos, os relatos de itens perdidos podem passar desapercebidos. Desta forma, o presente trabalho descreve uma proposta de um sistema acessível pela web que permita registrar e listar itens perdidos, reclamar e marcar os itens já devolvidos como achados, e notificar periodicamente aos usuários cadastrados melhorando o processo de identificação e reclamação pelos respetivos proprietários. É esperado que este sistema contribua significativamente para o bem-estar da comunidade estudantil sendo uma solução criada por membros, e para membros, da mesma.


# Facto e dimensões
![Modelo em estrla Perdidos e Achados](https://github.com/user-attachments/assets/9ffcea83-585e-4c87-9414-d17790a6bc62)

### dimEdificios: Dimensão dos edifícios
* Edificios - nome dos edifícios
* idEdificio - Id dos edificios


### dimCor: Dimensão das cores
* Cor - nome da cor
* idCor - idCores


### dimCalendario: Dimensão dos calendários
* Ano - Ano
* Data - Data DD/MM/YY
* Day - Dia 
* Month - Mês
* NomeMes - Nome do mês
* QuartoAno - Quarter year
* WeekMonth - número da semana no mês


### dimSala: Dimensão das salas
* idEdicio - id do Edifício
* idSala - id da Sala
* Sala - Nome da sala


### dimCategoria: Dimensão das categorias
* idCategoria - id da categoria
* Categoria - nome da categoria


### factoPerdidosAchados: Facto de itens perdidos e achados
* Data - data do acontecimento
* Estado - Estado. eg. perdido, achado ou recuperado
* Hora reporte - hora do acontecimendo
* idCategoria - id daCategoria
* idSala - id da Sala
* idEdificio - id do Edificio
* idCor - id da Cor
* Item - nome do item
---
# Processo ETL
https://github.com/Mauroreis100/Perdidos-e-Achados-ETL/blob/main/Perdidos%20e%20Achados%20ETL.ipynb

---
# P&A Insights
![P A Insights](https://github.com/user-attachments/assets/2fc78f5e-594c-431c-82f7-0eb933fecdf7)

# D1 Piso 1
![D1-P1](https://github.com/user-attachments/assets/d41f507f-97a1-4605-ba02-3829f9a3757e)

# D1 Piso 2
![D1-P2](https://github.com/user-attachments/assets/2efda07c-4457-4d9c-828c-4f5618ccb0eb)

# E Piso 1
![E-P1](https://github.com/user-attachments/assets/d459d96d-b95e-4c4c-a90b-5b3b578c81dd)

# E Piso 1
![E-P2](https://github.com/user-attachments/assets/de1413d1-c141-425d-944e-457a66a383cb)

# D2 Piso 1
![D2-P1](https://github.com/user-attachments/assets/dac25bcb-0295-41d3-8008-3b92a8d1118f)

---


# SM
![SM](https://github.com/user-attachments/assets/eff66eee-c8fe-44ee-bcfe-7db59ecc6b0e)

# Parque de Estacionamento
![Parque de Estacionament](https://github.com/user-attachments/assets/4f89117c-5e60-41aa-aec1-fe9caae22f1a)
----
Authors: Mauro Mahassa
---
Contact: mauromahassa@gmail.com
---
Project Continuity
This is project is complete
---
Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
