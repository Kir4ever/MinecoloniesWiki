---
title: Homepage
layout: default
---
# Добро пожаловать на вики MineColonies!

MineColonies - это интерактивный строительный мод, который позволяет вам создать свой собственный процветающий город в Minecraft.Это позволяет вашим лидерским навыкам расти, предоставляя вам все необходимое для построения своего королевства. MineColonies дает вам возможность создать такую же уникальную колонию, как и каждый игрок. Имея так много возможностей, вы будете каждый раз создавать новую колонию, адаптировать ее к любому биому, строить внутри горы, на вершине одной, под океаном или в небе.

Ваше воображение - ваш предел!

В MineColonies есть рабочие NPC, такие как [Строители](../../source/workers/builder), [Фермеры](../../source/workers/farmer), [Рыбаки](../../source/workers/fisher), [Лесорубы](../../source/workers/forester), [Стражи](../../source/workers/guard), [Шахтёры](../../source/workers/miner), [Плавильщики](../../source/workers/smelter), [Пекари](../../source/workers/baker), [Повары](../../source/workers/cook), [Курьеры](../../source/workers/courier), пять типов пастухов, [Компостерщики](../../source/workers/composter), и многое другое, и еще больше разрабатывается и добавляется по мере роста мода.

Он также включает в себя специализированные здания, такие как [Дом строителя](../../source/buildings/warehouse), [Дом](../../source/buildings/house), [Ратуша](../../source/buildings/townhall), [Барак](../../source/buildings/barracks), [Библиотека](../../source/buildings/library), [Университет](../../source/buildings/university), и конечно [Школа](../../source/buildings/school).

### Обратите внимание, что вики всегда ссылается на последнюю альфа-версию MineColonies 1.16.5!на

---

<div class="row">
{% for item in site.data.subnav.subnav %}
    <div class="col-lg col-md-3 col-sm-12 text-center">
        <h3 class="button p-1">{{ item.title }}</h3>
        {% for entry in item.subitems %}
            <a class="" href="{{ entry.url | relative_url }}">{{ entry.page }}</a><br />
        {% endfor %}
    </div>
{% endfor %}
</div>

---

MineColonies - это бесплатный мод с открытым исходным кодом, разработанный Let's Dev Together (LDT), некоммерческое сообщество. Исходный код доступен на [GitHub](https://github.com/ldtteam/minecolonies). Наши разработчики - это трудолюбивая, хорошо интегрированная команда разработчиков, которая постоянно добавляет больше контента, чтобы сделать MineColonies еще лучше. Тем не менее, мы всегда ищем больше людей, которые могут внести свой вклад в мод, будь то в качестве кодировщика, строителя, художника, актера озвучивания, редактора вики, тестировщика или просто поддерживая нас в [Patreon](https://www.patreon.com/minecolonies)!

Нашли ошибку? Сообщите об этом на [issue](https://github.com/ldtteam/minecolonies/issues/new/choose) чтобы помочь нам подарить вам лучший игровой опыт. Если вам нужна помощь или вы просто хотите присоединиться к беседе, загляните к нам в [Discord](https://discord.minecolonies.com)!
