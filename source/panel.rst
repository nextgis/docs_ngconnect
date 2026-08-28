Панель модуля
===============

В заголовке панели отображается домен Веб ГИС, к которой вы подключены в данный момент.

.. figure:: _static/connect_panel_ru_3.png
   :align: center
   :alt: Панель модуля расширения NextGIS Connect
   :width: 10cm
   
   Панель модуля расширения NextGIS Connect

.. |button_cloud_download| image:: _static/button_cloud_download.png
   :width: 6mm

.. |button_cloud_upload| image:: _static/button_cloud_upload.png
   :width: 6mm

.. |button_c_identify| image:: _static/button_c_identify.png
   :width: 6mm

.. |button_newfolder| image:: _static/button_newfolder.png
   :width: 6mm

.. |button_c_new_layer| image:: _static/button_c_new_layer.png
   :width: 5mm

.. |button_filter| image:: _static/button_filter.png
   :width: 6mm
   :alt: воронка

.. |button_refresh| image:: _static/button_refresh.png
   :width: 6mm

.. |button_openmap| image:: _static/button_openmap.png
   :width: 6mm
   :alt: карта с лупой

.. |button_settings| image:: _static/button_settings.png
   :width: 6mm
   :alt: синяя шестерёнка

.. |button_help| image:: _static/button_help.png
   :width: 6mm
   :alt: знак вопроса

На панели расположены следующие кнопки:

* |button_cloud_download| `Загрузить в QGIS <https://docs.nextgis.ru/docs_ngconnect/source/ngc_data_transfer.html>`_

* |button_cloud_upload| `Добавить в Веб ГИС <https://docs.nextgis.ru/docs_ngconnect/source/resources.html#ng-connect-export>`_

* |button_c_identify| Идентифицировать объекты в слоях Веб ГИС

* |button_newfolder| `Создать группу ресурсов <https://docs.nextgis.ru/docs_ngconnect/source/manage.html#ng-connect-res-group>`_ или |button_c_new_layer| `создать новый векторный слой <https://docs.nextgis.ru/docs_ngconnect/source/manage.html#new-vector-layer>`_

* |button_filter| `Фильтр и поиск ресурсов <https://docs.nextgis.ru/docs_ngconnect/source/filter.html>`_

* |button_refresh| `Обновить дерево ресурсов <https://docs.nextgis.ru/docs_ngconnect/source/panel.html#connect-refresh>`_

* |button_openmap| `Просмотр в браузере <https://docs.nextgis.ru/docs_ngconnect/source/panel.html#connect-open-webmap>`_

* |button_settings| `Настройки модуля <https://docs.nextgis.ru/docs_ngconnect/source/ngc_settings.html>`_

* |button_help| Справка - вы окажетесь здесь

Если на данный момент не настроено ни одно `подключение <https://docs.nextgis.ru/docs_ngconnect/source/ngc_install.html#ng-connect-new-connection>`_, вы увидите сообщение с предложением 
создать свою Веб ГИС.

.. figure:: _static/ngc_no_connection_ru.png
   :align: center
   :alt: Панель модуля расширения NextGIS Connect при отсутствии подключения
   :width: 10cm
   
   Панель модуля расширения NextGIS Connect при отсутствии подключения

Если ранее на устройстве использовалась версия NextGIS Connect, не поддерживавшая аутентификацию QGIS, то при включении обновленной версии будет предложено конвертировать существующие соединения и данные аутентификации. Это можно сделать через окно NextGIS Connect, а также `в настройках модуля <https://docs.nextgis.ru/docs_ngconnect/source/ngc_settings.html>`_.

.. figure:: _static/nextgis_connect/connect_update_convert_ru.png
   :align: center
   :name: connect_update_convert_pic
   :alt: Панель модуля расширения NextGIS Connect после обновления
   :width: 8cm

   Предупреждение о необходимости конвертации соединений

.. figure:: _static/nextgis_connect/ngc_upd_convert_menu_ru.png
   :align: center
   :name: ngc_upd_convert_menu_pic
   :alt: Настройки модуля расширения NextGIS Connect после обновления
   :width: 22cm

   Настройки модуля расширения NextGIS Connect после обновления с сообщением о конвертации





.. _connect_refresh:

Обновить
----------

Нажмите |button_refresh|, чтобы обновить всё дерево ресурсов Веб ГИС до актуального на текущий момент состояния.

.. figure:: _static/nextgis_connect/reload_ru.png
   :align: center
   :alt: Обновить дерево ресурсов
   :width: 10cm

   Актуализация данных Веб ГИС

.. _connect_open_webmap:

Просмотр в браузере
----------------------

Выберите в дереве ресурсов веб-карту (NGW Web Map) |resource_webmap|, галерею, слой или стиль, и нажмите |button_openmap|, чтобы открыть просмотр этого ресурса в новой вкладке браузера.

.. figure:: _static/nextgis_connect/open_webmap_ru.png
   :align: center
   :alt: Открыть веб-карту в браузере
   :width: 10cm

   Открытие веб-карты

Также это можно сделать через `контекстное меню <https://docs.nextgis.ru/docs_ngconnect/source/panel.html#ng-connect-cont-menu>`_.


.. _ng_connect_cont_menu:

Контекстное меню
----------------
Контекстное меню может отличаться у различных ресурсов. 

.. figure:: _static/context_menu_ru_2.png
   :align: center
   :alt: Контекстное меню qgis векторного слоя
   :width: 15cm
   
   Пример контекстного меню

Общедоступные операции для всех типов ресурсов:

- Открыть страницу ресурса - открывает страницу выбранного ресурса в Веб ГИС, также доступно из панели слоёв, см. :numref:`ngc_open_from_layertree_pic`;

- Переименовать ресурс;

- `Удалить ресурс <https://docs.nextgis.ru/docs_ngconnect/source/manage.html#connect-resource-delete>`_;

- Дерево - позволяет развернуть или свернуть все дочерние ресурсы.


Опциональные - зависят от типа ресурса:

- Добавить в QGIS и Добавить в QGIS как - операция и список ресурсов, для которых она доступна, описаны `в этом разделе <https://docs.nextgis.ru/docs_ngconnect/source/resources.html#ng-connect-export>`_;

- `Просмотр в браузере <https://docs.nextgis.ru/docs_ngconnect/source/panel.html#connect-open-webmap>`_ - доступен для веб-карт, галерей, слоёв и стилей, в браузере откроется веб-клиент с картой или страница превью слоя/стиля соответственно;

- История слоя - доступно для векторных слоёв с включённым версионированием, открывает в браузере `историю изменений слоя <https://docs.nextgis.ru/docs_ngweb/source/version.html#vers-ngw-view-history>`_;

- Создать новый ресурс:

  - `Веб Карту <https://docs.nextgis.ru/docs_ngconnect/source/manage.html#web-map>`_ - доступен для ресурсов: Векторный слой, Стиль Векторного слоя, Растровый слой, слой WMS;
  - `Сервис WFS <https://docs.nextgis.ru/docs_ngconnect/source/resources.html#wfs>`_ - доступен только для ресурсов Векторный слой, слой PostGIS;
  - `Сервис OGC API - Features <https://docs.nextgis.ru/docs_ngconnect/source/resources.html#ogc-api-features>`_ - доступен только для ресурсов Векторный слой и слой PostGIS;
  - `Сервис WMS <https://docs.nextgis.ru/docs_ngconnect/source/resources.html#wms>`_ - доступен только для ресурсов Векторный слой, Растровый слой, слой PostGIS;
  - `Форму сбора данных <https://docs.nextgis.ru/docs_ngweb/source/collector.html#collector-create-form>`_ - доступно для векторного слоя, откроется в браузере.

- `Загрузить как QML <https://docs.nextgis.ru/docs_ngconnect/source/export.html#connect-save-style>`_ - доступен только для ресурсов QGIS Стиль Векторного слоя и QGIS Стиль Растрового слоя;

- `Копировать стиль <https://docs.nextgis.ru/docs_ngconnect/source/edit.html#connect-style-copy>`_  - доступен только для ресурсов QGIS Стиль Векторного слоя и QGIS Стиль Растрового слоя;

- `Дублировать ресурс <https://docs.nextgis.ru/docs_ngconnect/source/ngc_data_transfer.html#connect-resource-double>`_ - доступен только для ресурсов: Векторный слой и Растровый слой;

- `Перезаписать выбранный слой <https://docs.nextgis.ru/docs_ngconnect/source/edit.html#connect-data-overwrite>`_ - доступен только для ресурсов Векторный слой и Растровый слой.




Кроме того, при установке модуля появляется возможность переходить к данным в Веб ГИС из панели слоев в QGIS: в контекстном меню слоя в QGIS найдите «NextGIS Connect», и нажмите «Открыть в Веб ГИС».


.. figure:: _static/nextgis_connect/ngc_open_from_layertree_ru.png
   :align: center
   :alt: Контекстное меню в дереве слоев
   :name: ngc_open_from_layertree_pic
   :width: 22cm

   Открытие данных в Веб ГИС из дерева слоев QGIS

.. |resource_webmap| image:: _static/symbol_webmap.png
   :width: 6mm