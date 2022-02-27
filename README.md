# hse_hw2_chip

## Bioinformatics Minor HSE HW-2

Ссылка на Colab ноутбук: https://colab.research.google.com/drive/1DOTPLhpIZAP6X9ye6EAK2OHBLMC5Hf8z?usp=sharing

Для исследования была выбрана клеточная линия Loucy и гистоновая метка H2AFZ.

## Анализ FastQC

HTML-выдачу FastQC см. в папке fastqc_reports.

### 1-ая ChipSeq реплика (ENCFF002AWQ)

![image](https://user-images.githubusercontent.com/60008375/155873370-581044e7-41af-421f-9b86-dc705775042e.png)

![image](https://user-images.githubusercontent.com/60008375/155873372-e65b9950-a118-47d9-b6df-db92942b760d.png)

Качество прочтений очень хорошее, все в зеленой зоне и даже не сильно падает к концу рида, что бывает свойственно для Иллюмины.

![image](https://user-images.githubusercontent.com/60008375/155873376-9c149020-5209-43e0-b3c0-6ae16ee4885d.png)

![image](https://user-images.githubusercontent.com/60008375/155874028-b031f905-5882-41f0-8aa4-c08b2726905d.png)

![image](https://user-images.githubusercontent.com/60008375/155873383-39d34875-8c89-463f-98a4-e2478ade15d6.png)

GC состав не идеальный, но близок к нормальному.

![image](https://user-images.githubusercontent.com/60008375/155873399-44560358-9274-4f7e-9fdb-f500a672885a.png)

Лишних адаптеров не обнаружено.

### 2-ая ChipSeq реплика (ENCFF002AXX)

![image](https://user-images.githubusercontent.com/60008375/155873606-a35448a3-a069-4c75-8da0-54f0610c75b2.png)

![image](https://user-images.githubusercontent.com/60008375/155873613-f4ef6be5-47a3-4546-8101-bf522831d91b.png)

Качество похуже, чем для первой реплики, но все так же в пределах зеленой зоны.

![image](https://user-images.githubusercontent.com/60008375/155873619-ba93e17b-a01b-4550-8f4b-18cd9f5f8361.png)

![image](https://user-images.githubusercontent.com/60008375/155873633-822bb99e-5236-4e70-ac62-77d1176f3cdf.png)

![image](https://user-images.githubusercontent.com/60008375/155873636-40a76a87-6274-449f-a873-34c319a4a090.png)

По последним двум графикам видно, что по GC составу немного "колбасит", но мы не можем на это повлиять.

![image](https://user-images.githubusercontent.com/60008375/155873648-2c5a5bdc-078c-4f90-9e41-21c09cf41371.png)

С адаптерами также все хорошо.

### Контроль (ENCFF775ENL)

![image](https://user-images.githubusercontent.com/60008375/155873807-2f05aca8-e4fd-458c-8718-dd6084ddec59.png)

![image](https://user-images.githubusercontent.com/60008375/155873817-80710647-67d0-48dc-84c8-55c73782e35a.png)

Качество ридов хорошее, все в зеленой зоне.

![image](https://user-images.githubusercontent.com/60008375/155873833-da8e0d2f-c271-48f1-8dbd-857d44d960b1.png)

![image](https://user-images.githubusercontent.com/60008375/155873840-67e04817-8208-42b8-9fe8-fcf984cadf0d.png)

![image](https://user-images.githubusercontent.com/60008375/155873847-f666a6a1-45f9-4af8-a163-c17495a4eafb.png)

GC-состав не так уж плох.

![image](https://user-images.githubusercontent.com/60008375/155873849-88024115-be6f-4814-b6e0-cbe85e1e9a25.png)

По адаптерам все супер.

**Вывод:** Подрезание чтений не требуется, качество ридов хорошее, можно продолжать работу.
