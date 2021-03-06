# Позиционни маркери (placeMarkers) #

* Автори: Noelia, Chris.
* Съвместимост с NVDA: от 2018.3 до 2019.1
* Изтегляне на [стабилна версия][1]
* Изтегляне на [тестова версия][2]

Тази добавка се използва за запазване и търсене на определен текст или
маркер в уеб страници или други документи в режим на разглеждане с
NVDA. Може също да бъде използвана за запазване или търсене на текстове в
многоредови контроли. Ако в такъв случай опресняването на каретката не е
възможно, отговарящият низ ще бъде копиран в клипборда, така че да може да
бъде намерен с други инструменти.  Добавката записва низовете и маркерите в
текстови файлове. Имената на тези файлове са базирани на името и URL адреса
на текущия документ. Тази добавка е базирана на добавките SpecificSearch и
Bookmark&Search, разработени от същия автор. Трябва да ги деинсталирате, за
да използвате тази, тъй като те имат еднакви клавишни команди и функции.

## Клавишни команди: ##

*	Control+Shift+NVDA+F: Отваря диалогов прозорец с поле за редактиране,
  който показва последното записано търсене. В този диалогов прозорец можете
  също да изберете предварително записани търсения от разгъващия се списък
  или да премахнете избрания низ от хронологията чрез поставяне на отметка в
  съответното поле. Можете да изберете дали текстът в полето за редактиране
  ще бъде добавен към историята на вашите записани текстове. И накрая,
  изберете действие от следващата група от радио бутони (между Търси
  следващ, Търси предишен или Не търси) и задайте дали NVDA ще взема предвид
  регистъра на буквите при търсенето. Когато натиснете OK, NVDA ще осъществи
  търсене на този низ.
*	Control+Shift+NVDA+K: Запазва текущата позиция като маркер. Ако желаете да
  добавите име към маркера, изберете някакъв текстов откъс от тази позиция,
  преди да го запазите.
*	Control+Shift+NVDA+Delete: Изтрива маркера, съответстващ на текущата
  позиция.
*	NVDA+K: Отива до следващия маркер.
*	Shift+NVDA+K: Отива до предишния маркер.
*	Control+Shift+K: Копира в клипборда името на файла без разширението, в
  който ще се съхраняват данните на позиционните маркери.
*	Alt+NVDA+K: Отваря диалогов прозорец с маркерите, запазени за този
  документ. Можете да напишете бележка за всеки маркер. Натиснете "Запази
  бележката", за да запишете промените. Натискането на "Изтрий" изтрива
  избрания маркер. Ако натиснете OK, можете да отидете до избраната позиция.
*	Не е зададено: Запазва позиция като временен маркер.
*	Не е зададено: Преминава към временния маркер за текущия документ.


## Подменю Позиционни маркери (NVDA+N) ##

Използвайки подменю Позиционни маркери, намиращо се в подменю Настройки от
главното меню на NVDA, имате достъп до:

*	Папка за конкретно търсене: отваря папката, където са записани предишните
  конкретни търсения.
*	Папка с маркери: Отваря папката със запазените маркери.
*	Копиране на папката с позиционни маркери: Можете да запазите папката с
  позиционни маркери.
*	Възстановяване на позиционните маркери: Може да възстановите вашите
  позиционни маркери от предишно съхранено копие на папката с вашите
  позиционни маркери.

Забележка: Позицията на маркерите се базира на броя на знаците. Поради това,
в страници с динамично съдържание е по-добре да използвате конкретното
търсене вместо маркерите.

## Промени във версия 12.0 ##
*	Отстранена е критична грешка, която предизвиква срив на NVDA при опит за
  отваряне на диалоговия прозорец "Бележки", ако преди запазването на
  отметки са избрани китайски символи.

## Промени във версия 11.0 ##
*	Съвместимост с NVDA 2018.3 и бъдещи версии (изисква се).
*	Ако е необходимо, можете да изтеглите [последната версия, съвместима с
  NVDA 2017.3][3].

## Промени във версия 10.0 ##
*	В Edge жестовете, обвързани с избора на маркери, като например NVDA+K,
  NVDA+Shift+K или NVDA+Alt+K, ще бъдат препредадени към приложението вместо
  да се опитва да се премести курсорът до маркери, с цел избягване на
  грешки, особено в големи документи.
*	Специфичното търсене вече се поддържа и за Edge.

## Промени във версия 9.0
*	При преместване към маркер от диалоговия прозорец "Бележки" курсорът за
  преглед следва системния курсор.
*	Командата за избор на предишния маркер отново работи правилно.
*	Маркерите могат да бъдат изтривани от диалоговия прозорец "Бележки"
*	Сега можете да назначите жестове, чрез които да запазите и да преминете
  към временен маркер за всеки документ.

## Промени във версия 8.0 ##
*	Премахнати са идентификатори на фрагменти от имената на маркерите, с което
  може да се избегнат проблеми в четеца за ePUB файлове "VitalSource
  Bookshelf".
*	Добавен е диалогов прозорец "Бележки" за добавяне на коментари към
  запазените маркери и отиване до избраната позиция.

## Промени във версия 7.0 ##
*	Диалоговият прозорец за записване на низ от текст за специфично търсене
  беше премахнат. Тази функционалност сега е включена в диалоговия прозорец
  Специфично търсене, който е преработен да позволява различни действия,
  когато бъде натиснат бутона OK.
*	Визуалното представяне на прозореца е подобрено, придържайки се към
  стандарта за изглед на прозорците, извеждани от NVDA.
*	Изпълняването на командата за намиране на предишен или следващ резултат от
  търсене в режим на преглед сега коректно ще извършва търсене на низа
  вземайки предвид регистъра на буквите, ако първоначалното търсене също ги
  е взимало предвид.
*	Изисква NVDA 2016.4 или по-нова.
*	Сега можете да зададете жестове за отваряне на диалоговите прозорци за
  копиране и възстановяване на позиционните маркери.
*	NVDA ще изведе съобщение, с което да ви извести при завършване на
  копирането или възстановяването на позиционните маркери в съответните
  диалогови прозорци.

## Промени във версия 6.0 ##
* Когато функциите на добавката са неизползваеми, жестовете биват
  препредавани към съответното приложение.

## Промени във версия 5.0 ##
* Добавена е опция за зачитане на малки/главни при търсене.
* Премахната е опцията за отваряне на помощната документация от менюто на
  Позиционни Маркери.
* По-интуитивни клавишни команди.

## Промени във версия 4.0 ##
* Премахнати са идентификатори на фрагменти от имената на маркерите, с което
  може да се избегнат проблеми в добавката ePUBREADER за Firefox.
* Помощта за добавката е достъпна от мениджъра на добавките.

## Промени във версия 3.1 ##
* Обновени преводи и нов език.
* Позицията на маркерите не бива съобщавана при бегло четене.

## Промени във версия 3.0 ##
* Добавена е поддръжка за бегло четене.

## Промени във версия 2.0 ##
* Добавени са опции за запазване и изтриване на различните търсения за всеки
  файл.
* Отстранен е проблем с пътищата на файловата система, които съдържат
  символи, различни от латиница.
* Бързите клавиши вече могат да бъдат преназначавани с използване на диалога
  Жестове на въвеждане на NVDA.

## Промени във версия 1.0 ##
* Първоначално издание.
* Добавката е преведена на: бразилски португалски, фарси, фински, френски,
  галицийски, немски, италиански, японски, корейски, непалски, португалски,
  испански, словашки, словенски, Тамил.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=pm

[2]: https://addons.nvda-project.org/files/get.php?file=pm-dev

[3]: https://addons.nvda-project.org/files/get.php?file=pm-o
