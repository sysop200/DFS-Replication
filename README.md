# DFS-Replication

Запуск этого сценария в PowerShell ISE даст вам хороший результат, сравнивая сервер, на котором он запущен, с другими участниками соединения в группе (ах) репликации, к которой он принадлежит.

Вы увидите «предупреждения», выделенные желтым цветом, и «ошибки», выделенные красным .

Поскольку это выполнялось в производственной среде, мне пришлось размыть имена серверов и имена групп репликации.
Он использует WMI для запроса групп репликации DFS и дальнейшего сбора статистики невыполненных работ.

# DFS Replilcation отправка отчета по почте
Я обновил скрипт, добавив возможность отправлять результаты по электронной почте.
