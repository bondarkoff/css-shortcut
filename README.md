## Install

NPM: `npm install css-shortcut`

YARN: `yarn add css-shortcut`

## Usage

Install package with NPM or Yarn.

### SASS/SCSS import

Open the main style file and import at the beginning `css-shortcut` from `node-modules` folder:
`@import 'node_modules/css-shortcut/index.min.css';`

### How To Use

Side => abbreviation:

-   `left` => `l`
-   `right` => `r`
-   `top` => `t`
-   `bottom` => `b`

### For Example:

| Classname           | Value                                                         |
| ------------------- | ------------------------------------------------------------- |
| `mr-12 mb-41`       | `margin-right: 12px; margin-bottom: 41px;`                    |
| `m-25`              | `margin: 25px;`                                               |
| `p-50`              | `padding: 50px;`                                              |
| `pr-10 mt-15 mb-15` | `padding-right: 10px; margin-top: 15px; margin-bottom: 15px;` |

### Margin

Margin from 1 to 50 pixels.

| Class  | Value             |
| ------ | ----------------- |
| m\*-1  | margin-\*: 1px;   |
| m\*-2  | margin-\*: 2px;   |
| m\*-3  | margin-\*: 3px;   |
| m\*-4  | margin-\*: 4px;   |
| m\*-5  | margin-\*: 5px;   |
| m\*-6  | margin-\*: 6px;   |
| m\*-7  | margin-\*: 7px;   |
| m\*-8  | margin-\*: 8px;   |
| m\*-9  | margin-\*: 9px;   |
| m\*-10 | margin-\*: 50px;  |
| etc.   | etc. (up to 50px) |

### Padding

Padding from 1 to 50 pixels.

| Class  | Value             |
| ------ | ----------------- |
| p\*-1  | padding-\*: 1px;  |
| p\*-2  | padding-\*: 2px;  |
| p\*-3  | padding-\*: 3px;  |
| p\*-4  | padding-\*: 4px;  |
| p\*-5  | padding-\*: 5px;  |
| p\*-6  | padding-\*: 6px;  |
| p\*-7  | padding-\*: 7px;  |
| p\*-8  | padding-\*: 8px;  |
| p\*-9  | padding-\*: 9px;  |
| p\*-10 | padding-\*: 50px; |
| etc.   | etc. (up to 50px) |

### Flex, display

| Класс      | Значение                        |
| ---------- | ------------------------------- |
| d-inblock  | display: inline-block;          |
| d-inflex   | display: inline-flex;           |
| d-flex     | display: flex;                  |
| d-block    | display: block;                 |
| d-grid     | display: grid;                  |
| jcsb       | justify-content: space-between; |
| jcsa       | justify-content: space-around;  |
| jcc        | justify-content: center;        |
| aic        | align-items: center;            |
| aie        | align-items: flex-end;          |
| ais        | align-items: flex-start;        |
| flex-col   | flex-direction: column;         |
| flex-row   | flex-direction: row;            |
| flex-wrap  | flex-wrap: wrap;                |
| flex-auto  | flex: 1 1 auto;                 |
| flex       | flex: 1;                        |
| m-auto     | margin: auto;                   |
| tac        | text-align: center;             |
| pos-r      | position: relative;             |
| pos-a      | position: absolute;             |
| pos-static | position: static;               |
| pos-sticky | position: sticky;               |

### Text

| Class     | Value                                                |
| --------- | ---------------------------------------------------- |
| tac       | text-align: center;                                  |
| ttc       | text-transform: capitalize;                          |
| ttu       | text-transform: uppercase;                           |
| ttl       | text-transform: lowercase;                           |
| tdn       | text-decoration: none;                               |
| tdu       | text-decoration: uderline;                           |
| td-dash   | text-decoration: dashed;                             |
| td-dot    | text-decoration: dotted;                             |
| td-double | text-decoration: double;                             |

### Font-Weight

| Class    | Value                  |
| -------- | ---------------------- |
| fw100    | font-weight: 100;      |
| fw200    | font-weight: 200;      |
| fw300    | font-weight: 300;      |
| fw400    | font-weight: 400;      |
| fw500    | font-weight: 500;      |
| fw600    | font-weight: 600;      |
| fw700    | font-weight: 700;      |
| fw800    | font-weight: 800;      |
| fw900    | font-weight: 900;      |
| fwbold   | font-weight: bold;     |
| fwnormal | font-weight: normal;   |

### Opacity

| Class | Value         |
| ----- | ------------- |
| op-1  | opacity: 0.1; |
| op-2  | opacity: 0.2; |
| op-3  | opacity: 0.3; |
| op-4  | opacity: 0.4; |
| op-5  | opacity: 0.5; |
| op-6  | opacity: 0.6; |
| op-7  | opacity: 0.7; |
| op-8  | opacity: 0.8; |
| op-9  | opacity: 0.9; |
| op-10 | opacity: 1;   |

### Other

| Class | Value                                                                                                        |
| ----- | ------------------------------------------------------------------------------------------------------------ |
| clear | Clears the base styles that the browser sets for: `<a>, <ul>, <li>`. And removed margins for all `<h>` tags. Also for all (*) other elements: `box-sizing: border-box; outline: none`                                      |
| c-p   | cursor: pointer |



