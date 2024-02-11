### Сериализатор и десериализатор для POJO в/из JSON
Классы в данном проекте позволяют сериализовать и десериализовать Plain Old Java Object в формат JSON.

На самом деле сериализуемые и десериализуемые объекты не полностью подходят под определение POJO, т.к.
сериализатор и десериализтор поддерживает наследование, коллекции (реализующие Collection) разной степени вложенности.
Также поддерживаютcя не все форматы JSON, удовлетворяющие [схеме](https://www.json.org/json-en.html)

### TODO:
* Сделать поддержку для всех форматов
