# Magics, DRY, SOLID
## Примененные принципы:
+ Правило Magic: не используй числа напрямую в коде.
  
    Переменные productNumber и productCount
  

+ Правило DRY: не повторяй свой код.

    Метод showShopAndBasket
  

+ Правило S - принцип единственной ответственности.

    Папка srpClasses в которой расположенны классы.
  

+ Правило O - принцип открытости/закрытости.

    Класс Product расшиерн интерфейсом CountChangable
  

+ Правило L-принцип замены Барбары Лисков.

    Наслдеников нет так как классы не расширяют друг друга.
  

+ Правило I- принцип сегрегации (разделения) интерфейса.

    В папке interfaces разделены интерфейсы Colorable и Printable

  
+ Правило D- принцип инверсии зависимостей.
  интерфейсы Colorable и Printable обеспечивают реализацию данного принципа.