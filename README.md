# AnalysisOfImageClassification
## Описание
  Необходимо проанализировать результаты и качество предсказаний модели детекции головы котов.
## Данные
<ul>
  <li>В папке images представлены изображения, по которым проводилась детекция</li>
  <li>В файле ground_truth.xlsx - разметка датасета
    <ul>
      <li>в столбце file указано название файла с изображением</li>
      <li>truth_label - класс объекта (0 - нет головы кота, 1 - есть голова кота)</li>
      <li>truth_bbox - бокс объекта</li>
    </ul>
  </li>
  <li>В файле predictions.xlsx - предсказания модели
    <ul>
      <li>в столбце file указано название файла с изображением</li>
      <li>pred_label - предсказанный класс объекта (0 - нет головы кота, 1 - обнаружена голова кота)</li>
      <li>pred_bbox - предсказанный бокс объекта</li>
    </ul>
  </li>
</ul>

## Бокс объекта
Бокс объекта представляет собой прямоугольник, записанный в четырех координатах:<br>
<br/>
**x**, **y**, **ширина**, **высота** - относительно ширины и высоты изображения, где **x** и **y** - это центр прямоугольника

