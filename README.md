# gnu-linux_lab6

- 1 Постановка задачи: изучение системных вызовов для обмена данными между процессами.
+ 2	Содержание этапов выполнения
  - 1 Запустить операционную систему.
  - 2 Войти в виртуальную машину, контейнер или на удалённый сервер приложений (IP адресом XX.XX.XX.254, пользователь lxc<NN>, пароль спросить у преподавателя).
### ![alt text](https://image.prntscr.com/image/Ct0JpmRmQ6u_BOhOkUx7PQ.png)
  - 3	В домашнем каталоге пользователя создать каталог work.
  - 4	Написать программу для обмена текстовыми сообщениями между процессами, с использованием механизма разделяемой памяти. Обеспечить синхронизацию обмена с помощью механизма семафоров.
   ### файл msgcli.c
   ![alt text](https://image.prntscr.com/image/G1wFWH-ERUqJc76MMZnbsQ.png)
   ### файл msgserv.c
   ![alt text](https://image.prntscr.com/image/lEpdjgwORVu_vP2_c0_fjQ.png)
  - 5	Написать makefile, обеспечивающий трансляцию, установку, очистку и удаление программы (см. лаб. 4)
   ### Makefile
   ![alt text](https://image.prntscr.com/image/-M-HwDUwQyWBtZq945uilQ.png)
  - 6	Оттранслировать программу и установить её в каталог bin каталога work с помощью команды make.
   ###
   ![alt text](https://image.prntscr.com/image/_a-_ZPC_SEmaNXcyT28svA.png)
  - 7	Очистить каталог work от вспомогательных файлов с помощью команды make.
  - 8	Запустить оттранслированную программу.
   ### 1-й результат работы:
   ![alt text](https://image.prntscr.com/image/i_89onnpT2_p656j1bkpnw.png)
   ### изменённый файл msgserv.c 
   ![alt text](https://image.prntscr.com/image/4GT0mekpQuqnxyHyhS1nfQ.png)
   ### 2-й результат работы:
   ![alt text](https://image.prntscr.com/image/UStuG0qVRBW7yJMPbf0UIg.png)
  - 9	Представить результаты выполнения работы преподавателю.
