<ol>
  <li> Слияние логов

  Решение представлено в json_merge.py</li>

  <li> Миграция базы данных
    <ul>
      <li>Добавить новую таблицу names с колонками id(Primary key) и name</li>
      <li>Заполнить новую таблицу именами и id's из основной таблицы</li>
      <li>Добавить в основную таблицу колонку name_id</li>
      <li>Обновить сервис А так, чтобы данные об именах писались как в name основной таблицы, так и в новую таблицу</li>
      <li>Обновить сервис Б так, чтобы брал имена из новой таблицы</li>
      <li>Обновить сервис А так, чтобы данные писались только в новом формате</li>
      <li>Удалить колонку name в основной таблице</li>
    </ul>
</li>
<ol>