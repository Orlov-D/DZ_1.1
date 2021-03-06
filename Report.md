# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

с 08.05.2021 - по 08.05.2021 было проведено тестирование сборки приложения Credit Card Number Validator.

На тестирование затрачено: 10 часов

В результате тестирования выявлены следующие дефекты:
* [Номера карт неравные 16 символов не проходят валидацию.](https://github.com/Orlov-D/DZ_1.1/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* IntelliJ IDEA Community Edition

В качестве тестовых данных использовались данные  https://www.freeformatter.com/credit-card-number-generator-validator.html:
* VISA:
  * 4716988961344135 Result is OK
  * 4929187036076896 Result is OK
  * 4485387290198324518 Result is OK
* MasterCard:
  * 5479575106606488 Result is OK
  * 5126106554154818 Result is OK
  * 5536385495088210 Result is OK
* Diners Club - North America:
  * 5590045657446522 Result is OK
  * 5559960224785906 Result is OK
  * 5583956997787848 Result is OK
* JCB:
    * 3531942555891865 Result is OK
    * 3539412466401552 Result is OK
    * 3539456204471535626 Result is OK    
* MIR:
  * 2201382000000013 Result is OK
* American Express (AMEX):
  * 344117488250694 Result is OK
  * 347812661326090 Result is OK
  * 374785399064918 Result is OK
* Diners Club - Carte Blanche:
  * 30209194423381 Result is OK
  * 30522139783127 Result is OK
  * 30039947347029 Result is OK

Тестирование производилось в следующем окружении:
* Windows 10 pro N (1809), x64
* версия Java 11.0.10
