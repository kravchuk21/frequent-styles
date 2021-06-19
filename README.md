# frequent-styles
> Набор часто используемых css-классов

# Установка
**Npm**
```
npm install --save frequent-styles
```
**Yarn**
```
yarn add frequent-styles
```
# Использование

> ## Margin и padding отступы
### Сокращения:
 - `left` => `l`
 - `right` => `r`
 - `top` => `t`
 - `bottom` => `b`
 - `margin` => `m`
 - `padding` => `p`
### Основные значения:  `5, 10, 15, 20, 25, 30, 35, 40, 45, 50, 75, 100`
### Примеры:

| Класс               | Значение                                                      |
| ------------------- | ------------------------------------------------------------- |
| `mr-10 mb-50`       | `margin-right: 10px; margin-bottom: 50px;`                    |
| `m-25`              | `margin: 25px;`                                               |
| `p-50`              | `padding: 50px;`                                              |
| `pr-35 pl-100`      | `padding-right: 35px; padding-left: 100px;`                   |

> ## Display стили
### Сокращения:
  - `width` => `w`
  - `height` => `h`
  - `display` => `d`
  - `position` => `pos`
  - `cursor` => `cu`
### Примеры:
| Класс               | Значение                                                      |
| ------------------- | ------------------------------------------------------------- |
| `w100 h100`| `width: 100%; height: 100%;`|
| `d-ib d-if d-block d-flex`| `display: ( inline-block / inline-flex / block / flex );`|
| `justify-between justify-around justify-center justify-end`| `justify-content( space-between / space-around / center / flex-end )`|
| `align-center align-end align-start`| `align-items: ( center / flex-end / flex-start );`|
| `flex-column flex-row`| `flex-direction: ( column / row );`|
| `m-auto ml-auto mr-auto`| `margin: auto; margin-left: auto; margin-right: auto;`|
| `text-center`| `text-align: center;`|
| `text-capitalize text-uppercase text-lowercase`| `text-transform: ( capitalize / uppercase / lowercase );`|
| `text-truncate`| `white-space: nowrap; overflow: hidden; text-overflow: ellipsis;`|
| `opacity-( 1-10 )`| `opacity: ( 0-1 );`|
| `pos-r pos-a`| `position: ( relative / absolute );`|
| `cu-p`| `cursor: pointer;`|
