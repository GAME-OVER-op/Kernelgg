# Magisk Kernelgg Manager

**Magisk Kernelgg Manager** — это модуль для Magisk, позволяющий включать и отключать ядра процессора на устройствах с root-доступом. Скрипт взаимодействует с файловой системой устройства через интерфейсы `/sys/devices/system/cpu/` и позволяет пользователю управлять состоянием ядер в зависимости от их потребностей.

## Функциональность

- **Автоматическое определение количества ядер** — скрипт сам определяет количество доступных ядер на устройстве.
- **Управление состоянием ядер** — можно включать или отключать ядра, что может помочь в оптимизации работы устройства.
- **Вывод информации о состоянии ядер** — скрипт выводит список всех ядер с указанием их текущего состояния (включено/выключено).
- **Поддержка Magisk** — модуль интегрируется с Magisk для простоты установки и использования.

## Использование

1. Запустите модуль через Magisk Manager.
2. В меню выберите нужное действие:
   - Включить или отключить ядро.
   - Просмотреть список доступных ядер и их состояние.
3. Следуйте инструкциям на экране.

## Особенности

- **Root-доступ обязателен** — модуль требует наличия root-доступа для работы.
- **Поддержка всех популярных архитектур** — работает на устройствах с архитектурами ARM и ARM64.
- **Будущее развитие** — проект будет активно развиваться, добавляться новые функции для более гибкого управления ядрами и оптимизации работы устройства.

## Разработка

Проект находится в активной разработке и в будущем будет обновляться с добавлением новых функций, таких как:
- Управление частотами ядер.
- Автоматическая оптимизация на основе режима работы устройства.
- Поддержка дополнительных настроек производительности.

Если у вас есть предложения или вопросы, пожалуйста, создайте [issue](https://github.com/your-username/magisk-kernel-manager/issues) или отправьте pull request.

## Важное предупреждение

**Использование этого модуля может повлиять на работу вашего устройства.** Отключение ядер процессора или изменение их состояния может повлиять на стабильность системы и привести к перегреву устройства, сбоям или даже повреждению компонентов.

**Мы не несем ответственности за повреждения устройства или любые другие негативные последствия**, которые могут возникнуть в результате использования этого модуля. Пожалуйста, используйте данный модуль на свой страх и риск. Убедитесь, что вы понимаете все возможные последствия и всегда делаете резервные копии данных перед использованием.

Если вы не уверены в своих действиях, не используйте данный модуль!
