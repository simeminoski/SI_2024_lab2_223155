Simeon Minoski 223155
2.Control Flow Graph го направив со помош на https://app.diagrams.net
![CFG](https://github.com/simeminoski/SI_2024_lab2_223155/assets/165807724/beb32d54-9c44-4937-afdc-d6b6632d54df)

3.цикломатската комплексност на дадениот код е 10;
цикломатска комплексност=Број на ребра - Број на темиња -2*неповрзани темиња;темето 27 не се поврзува кон никое друго теме значи 1.
цикломатска комплексност=40 - 32 -2*1;
4.  
Тест случај 1: allItems е null
Тест случај 2: Објект со празно име и валиден баркод
Тест случај 3: Објект со невалиден баркод
Тест случај 4: Објект со валиден баркод и попуст
Тест случај 5: Објект со валиден баркод без попуст
Тест случај 6: Објект со попуст, цена над 300 и баркод почнува со '0'
Тест случај 7: Сума поголема од payment
Тест случај 8: Сума еднаква или помала на payment

5.
if (item.getPrice() > 300 && item.getDiscount() > 0 && item.getBarcode().charAt(0) == '0')
има три подуслови па имаме 2*2*2=8 вкупно случаи
1.item.getPrice() > 300 && item.getDiscount() > 0 && item.getBarcode().charAt(0) == '0'
2.item.getPrice() > 300 && item.getDiscount() > 0 && item.getBarcode().charAt(0) != '0'
3.item.getPrice() > 300 && item.getDiscount() <= 0 && item.getBarcode().charAt(0) == '0'
4.item.getPrice() > 300 && item.getDiscount() <= 0 && item.getBarcode().charAt(0) != '0'
  5.item.getPrice() <= 300 && item.getDiscount() > 0 && item.getBarcode().charAt(0) == '0'
  6.item.getPrice() <= 300 && item.getDiscount() > 0 && item.getBarcode().charAt(0) != '0'
  7.item.getPrice() <= 300 && item.getDiscount() < 0 && item.getBarcode().charAt(0) == '0'
  8.item.getPrice() <= 300 && item.getDiscount() < 0 && item.getBarcode().charAt(0) != '0'

