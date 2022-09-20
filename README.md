## Шаблон гитхаба для сдачи задач по курсу "Алгоритмы и структуры данных"

> Все сдаваемые задачи должны быть написаны на языке С++

> Код, выкладываемый в репозиторий, должен пройти все тесты в тестирующей системе 

### Подготовка репозитория:
1. Зарегистрируйтесь в гитхабе, если вы этого еще не сделали
2. Создайте репозиторий. [Как это сделать тут](https://docs.github.com/en/get-started/quickstart/create-a-repo). 

**Важно:** делайте репозиторий ***приватным***

3. В README.md напишите: Имя, Фамилия, номер группы
4. Добавьте меня (PolinaChubenko) в коллабораторы. [Инструкция тут](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository).


### Как заливать задачи:
- создайте в ветке main папку вида: ```1contest```. 
- создаете новую ветку с названием вида: ```1contest_taskA``` ([подробнее тут](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository)). 

**Важно:** новая ветка создается из ветки main
- переключаетесь на созданную ветку и в папку ```1contest``` заливаете ваше решение в файл ```taskA.cpp```

### Как сдавать задачи:
После того, как вы зальете решение, создайте Merge Request на слияние вашей ветки с веткой ```main```. [Как это сделать тут](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

**Важно:** нажимать на кнопку ```Merge pull request``` ***не нужно***.

Потом ваша задача будет проверена. Если все хорошо, то MR будет закрыт и ваше решание окажется в ветке ```main```. Если по коду будут замечания, то они появятся в комментариях к MR-у. Чтобы внести правки в решения, перейдите на ветку с вашей задачей и отредактируйте файл с кодом. Все изменения автоматически подтянутся в MR. После перепроверки и отсутсвия недочетов решение будет смерджено.

> Учтите, что на проверку решения нужно время. Ассистент тоже человек, иногда спит / ест / живет своей жизнью и т.д., поэтому заливать все на гитхаб в последний момент - это очень плохая идея. 
