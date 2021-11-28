# Cравнение RNA-seq данных перепрограммированных и контрльных мышиных эмбриональных фибробластов (MEFs) и нахождение генов, которые наиболее сильно изменяют свою экспрессию.
RNA-seq образцы:
- Перепрограммированные: SRR3414629, SRR3414630, SRR3414631 
- Контрольные образцы: SRR3414635, SRR3414636, SRR3414637

Выравнивание RNA-seq чтений на геном мыши:
https://colab.research.google.com/drive/1J_qbV2nfrhzDNL1IvLjTHkdynYDLEg-o?usp=sharing

[Отчёты FastQC](/data/FastQC_Reports.md)![143770829-56c9b381-47af-48bc-b202-f6c05bcdf0d2](https://user-images.githubusercontent.com/60548614/143770849-86c152df-ea89-4853-93f1-e76ef5bc6f8f.png)


Общее кол-во чтений, и кол-во, которое удалось успешно откартировать: 
![image](https://user-images.githubusercontent.com/60548614/143770815-d9947b83-cdb9-45c2-989f-2613a558f2c8.png)
![image](https://user-images.githubusercontent.com/60548614/143770829-56c9b381-47af-48bc-b202-f6c05bcdf0d2.png)

Количество уникально-картированных чтений:![image](https://user-images.githubusercontent.com/60548614/143773136-44db945a-ab8b-4ba9-b2bd-b45fb33bbdc6.png)

Количество чтений, которые не удалось приписать ни одному гену:
![image](https://user-images.githubusercontent.com/60548614/143773222-1aa4efee-f9a8-46af-b88d-337f01abb798.png)

Общее число чтений, соответствующих хотя бы одному гену:
![image](https://user-images.githubusercontent.com/60548614/143773272-28045670-cebf-44ea-9286-afab1422086a.png)


Поиск генов, которые значимо поменяли свою экспрессию в результате перепрограммирования:
https://colab.research.google.com/drive/1XsEvLo6LpbIJqadCJgtrobu0397EnWzu?usp=sharing
