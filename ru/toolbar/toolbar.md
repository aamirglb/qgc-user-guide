# Панель инструментов

The main toolbar provides access to select the different application views, and high level status information for connected vehicles. The toolbar is the same in all views except for "PlanView" (which has a single icon to take you back to "Fly" view).

## View-select icons

The following icons are used to switch between the main *Views*. These are displayed even if no vehicle is connected.

![Settings view icon](../../assets/toolbar/toolbar_view_select_settings.jpg) **[Настройки](../SettingsView/SettingsView.md)** <br />Настройка *приложения QGroundControl*.

![Setup view icon](../../assets/toolbar/toolbar_view_select_setup.jpg) **[Настройка](../SetupView/SetupView.md)** <br />Настройка и настройка БПЛА.

![Plan view icon](../../assets/toolbar/toolbar_view_select_plan.jpg) **[План](../PlanView/PlanView.md)** <br />Планирование и создание автономных планов полетов.

![Fly icon](../../assets/toolbar/toolbar_view_select_fly.jpg) **[Fly](../FlyView/FlyView.md)** <br />Monitor your vehicle(s) while flying, including streaming video.

![Analyze icon](../../assets/toolbar/toolbar_view_select_analyse.jpg) **[Анализ](../analyze_view/README.md)** <br />Скачивание журналов событий, запись географических метаданных в фотографии на основе трека полета, доступ к консоли MAVLink.

## Символы состояния

Символы статуса активны, когда *QGroundControl* подключено к полётному контроллеру. Они сигнализируют об уровнях состояния основных систем необходимых для навигации БПЛА и могут быть нажаты для получения более подробной информации.

![](../../assets/toolbar/toolbar_status_message.jpg) ![yield](../../assets/toolbar/toolbar_status_critical.jpg) **Vehicle Messages** <br />Click to show a list of messages from the vehicle. Note that version on the right is displayed when there are critical messages.

![](../../assets/toolbar/toolbar_status_gps.jpg) **GPS Status** <br />Shows you satellite count and curent HDOP.

![](../../assets/toolbar/toolbar_status_rc.jpg) **RC RSSI** <br />RC signal strength information.

![](../../assets/toolbar/toolbar_status_telemetry.jpg) **RSSI Телеметрии ** <br />Информация об уровене сигнала канала телеметрии.

![](../../assets/toolbar/toolbar_status_battery.jpg) **Батарея** <br />Информация об остаточной емкости батарее (в процентах).

![](../../assets/toolbar/toolbar_status_flight_mode.jpg) **Режимы полета** <br />Текущий режим полета. Нажмите, чтобы изменить режим полета.

![](../../assets/toolbar/toolbar_status_rtk_gps.jpg) **RTK GPS Survey-In Status** <br />Shows you progress of RTK GPS Survey-In process.