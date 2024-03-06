//вблок try пишем проблемный код
try {
//Reference error
a++
console.log('after error')
} catch (error) {
console.log('SORRY: ', error)
}
// name - тип ошибки
// TypeError
// SyntaxError
// ReferenceError

// message - тело ошибки

// stack - место в котором ошибка возникла

// код в блоке try после ошибки не отрабатывает
// он сразу перекидывает в catch
// если нет ошибок, то catch не отрабатывает

// try - попытка попытаться
// catch - ловить
// uncaught - непойманный
// uncaght - ошибка не в блоке catch

// Когда код выдает непойманную ошибку
// скрипт перестает выполняться

console.log('CODE WORKS')