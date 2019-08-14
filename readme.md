Документация по API

/ получить список задач
Route :: get ('tasks', 'TaskController @ index');
// получить конкретное задание
Route :: get ('task / {id}', 'TaskController @ show');
// создаем новое задание
Route :: post ('task', 'TaskController @ store');
// обновить существующую задачу
Route :: put ('task', 'TaskController @ store');
// удаляем задачу
Route :: delete ('task / {id}', 'TaskController @ destroy');
