Используя данный проект можно получить курсы валют по отношению к рублю. Данные берутся с сайта CBR(Центральный банк России)


Обращение следующее:
  
  kurs := kurs.GetKurs() // Вызов функции которая получит данные
	fmt.Println(kurs.Valute.USD)// Вывод информации по Доллару. Внутри можно обратится отдельно к Значению наименованию и прочему.

 fmt.Println(kurs.Valute.USD.Value) // Вывод - 96.6472 (ну или другое, зависит от дня в который решили проверить)
 
