## Принцип разделения интерфейсов

Если клиент не зависит от какого-то метода, то изменение когда этого метода не должно никак влиять на клиента. Если интерфейсы изолированы друг от друга, при изменении одного какого-то интерфейса, остальные не должны слететь. Например, если на сайте ozon придумали какую-то новую фичу для продавцов, от этого не должен ломаться интерфейс для покупателей.