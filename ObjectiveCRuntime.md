# Objective-C Runtime

Библиотека времени исполнения, которая функционирует прямо во время исполнения приложения и предоставляет поддержку динамических свойств для Objective-C. Разработчику приложений на Swift не нужно знать деталей ее использования, нужно лишь понимать, что ее возможности опосредованно используются в процессе создания приложения (примеры рассмотренны ниже). 

## Содержание

- [Аттрибут `@objc`](/Ch-ObjectiveCRuntime.md#objc)

## <a id="objc"></a> Аттрибут `@objc`

Аттрибут `@objc` позволяет сделать метод или свойство, написанное на Swift, видимым для Objective-C Runtime.

Например, метод addtarget