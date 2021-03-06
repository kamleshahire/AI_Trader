# AI_Trader

**Artificial Intelligence Trader**

Concept for this application is to provide interface to financial trading data (historical from Cloud Firebase db, streaming via REST API) and to build machine learning algorithms to predict future price.

AI Trader will provide platform to test various financial strategies before going live with your real money.

Software development fully support TDD and Agile practices (eg. DevOps, Design Thinking) while backlog and upcoming sprints can be checked via public [trello board](https://trello.com/b/cDSR6XFI/ai-trader-sprints).

Anyone is welcome to join this project (contact szczesny.piotr@outlook.com) to improve your android development skills.


| Platform         | Build Status |
|:----------------:|:------------:|
| Android develop  | [![CircleCI](https://circleci.com/gh/Hortensie/AI_Trader/tree/develop.svg?style=shield)](https://circleci.com/gh/Hortensie/AI_Trader/tree/develop) |
| Android master   | [![CircleCI](https://circleci.com/gh/Hortensie/AI_Trader/tree/master.svg?style=shield)](https://circleci.com/gh/Hortensie/AI_Trader/tree/master) |
| Code Coverage develop | [![codecov](https://codecov.io/gh/Hortensie/AI_Trader/branch/develop/graph/badge.svg)](https://codecov.io/gh/Hortensie/AI_Trader) |
| Code Coverage master  | [![codecov](https://codecov.io/gh/Hortensie/AI_Trader/branch/master/graph/badge.svg)](https://codecov.io/gh/Hortensie/AI_Trader) |


Following tools are being used in this project:

- Android Studio with SDK / NDK support
- Version Control GitHub + GitFlow / Circle CI
- Testing via Junit4 / Robolectric / Mockito / Espresso (UI)
- Code coverage via codecov.io
- Google Engine (Firebase db)
- OOP practices like (KISS/OCP/DRY/SRP/LSP)
- more incoming like Vulkan API to draw charts or GPU processing for machine learning, Spark for queries