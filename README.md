В этом домашнем задании Вам необходимо сделать следующее.

1) Весь элемент <mat-card> с прошлого домашнего задания, который соответствует одной карточке переместить внутрь нового компонента <film-item>, а компонент <films> переименовать (пересоздать) как компонент <film-list>(или <films-list>). Сделать это таким образом, чтобы компонент <film-item> был дочерним компонентом <film-list>(или <films-list>).
В родительском компоненте с помощью *ngFor вывести дочерние <film-item> и передать в них через property binding все данные, которые необходимые для отображения фильма. Эти данные нам доступны из нашего сервиса FilmService.

2*) В заготовке уже есть готовая примерная верстка элемента с селектором из библиотеки Angular Material, который позволяет выбирать тип сортировки карточек с фильмами. Вам необходимо разобраться, как работает селектор и реализовать сортировку в алфавитном порядке по названию карточек с фильмами.

3) Реализовать механизм передачи события с вложенного компонента во внешний (родительский), как было показано на сессии. В заготовке у Вас будет рабочий пример.
Вам необходимо реализовать следующее. При нажатии на кнопку “Добавить в избранное” на карточке с фильмом с помощью механизма event binding передать данные на компонент верхнего уровня <film-list>(или <films-list>) и в нем обновить счетчик, который будет отображать общее число добавленных в избранное.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
