Template Method{
1.Позволяет
определить общий алгоритм создания отчета в одном месте
переопределять отдельные шаги в дочерних классах
уменьшить дублирование кода
легко добавлять новые типы отчетов

2.Новый класс, который наследуется от ReportGenerator, и реализовать методы
CreateHeader()
FormatData()
CreateBody()

3.Абстрактные методы
CreateHeader()
FormatData()
CreateBody()

Hook-методы
CustomerWantsSave()
CustomerWantsEmail()
SaveReport()
}

