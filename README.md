# Теория систем массовго обслуживания 

## Моделирование ситемы с конечным числом узлов с поломками 

Задача: 

Производственная система состоит из m станков,каждый из которых подвержен случайным поломкам.  Перед поломкой станок работает в течение промежутка времени, который представляет собой экспоненциально распределенную случайную величину со средним значением 8 часов.  Ремонтом станков занимается s ремонтников(где s — фиксированное положительное целое число). Для того, чтобы починить один станок, одному ремонтнику требуется экспоненциально распределенный промежуток времени со средним значением 2 часа; Ремонтом сломанного станка может заниматься только один ремонтник, даже если в это время есть другие свободные ремонтники. Если одновременно ломается более s станков, они формируют очередь на ремонт с дисциплиной FIFO и ждут первого свободного ремонтника.  Далее ремонтник чинит сломанный станок до тех пор, пока он не будет починен, независимо от того, что еще происходит в системе.  Предположим, что каждый час поломки одного станка стоит 50 долларов, а час работы ремонтника стоит 10 долларов.  (Ремонтникам платят почасовую оплату независимо от того, работают ли они на самом деле.)


Предположим, что количество станков в системе равно m = 5, но напишите общий код, позволяющий учитывать значение m, достигающее 20, путем изменения входного параметра.


Смоделируйте систему ровно при 800 часах работы для каждой стратегии занятости ( s = 1, 2, 3, 4, 5 ) ,  чтобы определить, какая из них приводит к наименьшим ожидаемым средним затратам в час, допустив, что в момент времени 0 все машины только что были отремонтированы.


### From Simulation modeling and analysis / Averill M. Law, President Averill M. Law & Associates, Inc.Tucson, Arizona, USA, www.averill-law.com. — Fifth edition

(original text) 

1.22. A manufacturing system contains m machines, each subject to randomly occurring breakdowns. A machine runs for an amount of time that is an exponential random variable with mean 8 hours before breaking down. There are s (where s is a fixed, positive integer) repairman to fi x broken machines, and it takes one repairman an exponential amount of time with mean 2 hours to complete the repair of one machine; no more than one repairman can be assigned to work on a broken machine even if there are other idle repairmen. If more than s machines are broken down at a given time, they form a FIFO ``repair” queue and wait for the first available repairman. Further, a repairman works on a broken machine until it is fixed, regardless of what else is happening in the system. Assume that it costs the system $50 for each hour that each machine is broken down and $10 an hour to employ each repairman. (The repairmen are paid an hourly wage regardless of whether they are actually working.) Assume that m = 5, but write general code to accommodate a value of m as high as 20 by changing an input parameter. Simulate the system for exactly 800 hours for each of the employment policies s = 1, 2, . . . , 5 to determine which policy results in the smallest expected average cost per hour. Assume that at time 0 all machines have just been “freshly” repaired. 
