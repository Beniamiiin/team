### Начало нового проекта

#### Выбор bundle id
Для bundle id используется идентификатор вида `ru.ramblerco.[название компании].[название проекта]`.

**Примеры:** `ru.ramblerco.rambler.mail`, `ru.ramblerco.rambler.news`, `ru.ramblerco.afisha.restaurants`.

#### GitLab
В namespace `ramblerco-ios` на [корпоративном GitLab](https://gitlab.rambler.ru/ramblerco-ios/) создайтеновый проект. Название репозитория должно совпадать с bundle id.

#### Continuous Integration
Используя [инструкцию](/processes/continuous-integration/jenkins-ci-setup.md), настройте Continuous Integration для нового проекта на [Jenkins](http://ci.dev.rambler.ru/jenkins/).

#### Continuous Delivery
Используя [инструкции](/processes/continuous-delivery/continuous-delivery.md#Настройка), настройте Continuous Delivery, в том числе и ночные сборки, для нового проекта на [Jenkins](http://ci.dev.rambler.ru/jenkins/).

#### Upsource
Попросите вашего руководителя настроить новый проект на [Upsource](http://upsource.rambler-co.ru/).