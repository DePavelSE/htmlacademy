Ширина и высота элементов задаются с помощью свойств width и height соответственно.

По умолчанию блочные элементы занимают всю доступную ширину, которая равна ширине родительского контейнера или окна браузера.

Высота по умолчанию блочных элементов зависит от их содержимого. Если задать блочному элементу ширину и высоту так, что содержимое элемента не будет в него помещаться, то оно как бы «выпадет» из него.

Строчные элементы не реагируют на задание ширины и высоты в CSS.

Задать ширину блоку можно, например, так:

.selector {
    width: 100px;
    height: 100px;
}

Вернуть значения по умолчанию можно с помощью специального значения auto:

.selector {
    width: auto;
    height: auto;
}
