Работа с этой конкретной API довольно легко, но есть несколько некоторые аспекты вы уже должны знать о, в противном случае ваша жизнь может стать немного сложнее. Позвольте мне дать вам некоторые подсказки: Прежде всего, мы не будем использовать любую SDK, или IOS-конкретной библиотеки. Вместо этого, мы будем делать простые HTTP запросы GET запросы (на самом деле), чтобы получить данные из Google. Результаты в формате JSON, так что это необходимо, вы уже знаете, как данные формируются в формате JSON. Вы не должны быть экспертом JSON; просто чтобы понять формат.
 
Я начну представлять демонстрационное приложение мы собираемся развиваться в этом уроке, говоря сначала, что у вас есть, чтобы загрузить проект стартера, который будет ваша точка интро. В ней вы найдете интерфейс и необходимые свойства и методы IBOutlet IBAction уже определены и связаны, а также любой другой необходимый код, так что здесь мы просто сосредоточиться на реализации логики приложения

Это просто демо, что показывает вам, как интегрировать приложение с YouTube API. Вы можете
найти полное руководство здесь:

Для запуска демо-версию, вы должны создать свой собственный ключ API первым и обновить следующую строку кода в ViewController.swift:

var apiKey = "YOUR_API_KEY_HERE"# youtube-api
