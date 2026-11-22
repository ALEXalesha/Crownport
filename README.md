# Crownport

![Status](https://img.shields.io/badge/status-в%20разработке-orange) ![Release](https://img.shields.io/badge/release-не%20выпущено-lightgrey) ![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.8%20C%2B%2B-black) ![Platform](https://img.shields.io/badge/platform-Windows%20x64-blue) ![License](https://img.shields.io/badge/license-All%20rights%20reserved-lightgrey) ![Built with Claude Code](https://img.shields.io/badge/Built%20with-Claude%20Code-8A2BE2)

Код, тесты и документацию пишет Claude (Anthropic) в Claude Code; идея, проверка и решения - автора репозитория.

Игра в открытом мире на Unreal Engine 5: свой большой город Crownport у моря и вся округа вокруг него - горы, леса, река,
порт, аэропорт, космодром. Машины, самолёты, вертолёты, лодки и ракеты, живой город с трафиком и пешеходами, полиция и
розыск, подработки и гонки, сюжетные миссии. Жанр - городская песочница, но мир, названия, герой и история свои.

**Состояние: в разработке, ничего не выпущено.** Здесь только описание игры, исходный код закрыт.

*English:* Crownport is an open-world game on Unreal Engine 5 (C++ only): an original coastal city and its countryside -
mountains, forests, a river, a port, an airport and a spaceport; cars, planes, helicopters, boats and rockets; living
traffic and pedestrians, police, side jobs, races and story missions. Work in progress, nothing released yet. Closed source. All rights reserved, see [LICENSE](LICENSE).

## Почему так сделано

- **Только C++, без Blueprint.** Всё, что можно, создаётся кодом и скриптами: так любой шаг повторяется одной командой, а
  правила игры проверяются автоматическими тестами.
- **Мир продуман, а не насыпан.** У каждого района есть причина быть именно там (порт - в бухте, космодром - на мысу, чтобы
  ракеты уходили над морем), у каждой дороги - куда она ведёт. Пустых мест нет: в любой клетке карты 250 x 250 м есть
  что-то, ради чего туда ехать. Это проверяется законом-тестом по карте.
- **Наработки других игр.** Физика грязи и колеи - из MudTrail, повреждения машин - из Horizon Drift, сборка ракет - из
  OrbitForge, стрельба и камера с груди - из RustFoundry, модели - общий набор ModelKit (Blender).

## Что будет

| Раздел | Что задумано |
|---|---|
| Мир | больше 10 x 10 км: город, пригороды, горы до ~1200 м, леса, река с плотиной и озером, побережье, 12 районов |
| Транспорт | машины, внедорожники, грузовики, мотоциклы, самолёты, вертолёты, лодки, ракеты, поезда и метро |
| Жизнь города | трафик по правилам, пешеходы со своим распорядком, сутки и погода, радио, магазины и часы работы |
| Игра | песочница, сюжет с одним героем, полиция и розыск, подработки, гонки и ралли, дома и гараж |
| Вид | реализм UE5 (Lumen, Nanite), третье лицо с переключением на первое |
| Сеть | сначала одиночная игра, код сразу под сетевую игру Unreal |

## Лицензия

Исходный код закрыт. Все права защищены, см. [LICENSE](LICENSE).
