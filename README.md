
[![BuyMeACoffee](https://user-images.githubusercontent.com/99820593/232435884-10ad52e3-a7e6-4b08-9053-9f261f6133fd.png)](https://www.buymeacoffee.com/bondarkoveg)

### if you would like to support the development of the project, you can [Donate](https://www.buymeacoffee.com/bondarkoveg)

## Install

NPM: `npm install css-shortcut`

YARN: `yarn add css-shortcut`

## Usage

Install package with NPM or Yarn.

### SASS/SCSS import

Open the main style file and import at the beginning `css-shortcut` from `node-modules` folder:
`@import 'node_modules/css-shortcut/index.min.css';`

### React import

Open the main react file and at the beginning type `import 'css-shortcut'`

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
| m\*-10 | margin-\*: 10px;  |
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
| p\*-10 | padding-\*: 10px; |
| etc.   | etc. (up to 50px) |

### Top, right, bottom, left

Top, right, bottom, left from 0 to 50 in pixels.

| Class     | Value         |
| --------- | ------------- |
| top-0     | top: 0px;     |
| top-2     | top: 2px;     |
| top-50    | top: 50px;    |
| right-0   | right: 0px;   |
| right-2   | right: 2px;   |
| right-50  | right: 50px;  |
| left-0    | left: 0px;    |
| left-2    | left: 2px;    |
| left-50   | left: 50px;   |
| bottom-0  | bottom: 0px;  |
| bottom-2  | bottom: 2px;  |
| bottom-50 | bottom: 50px; |
| etc.      | etc.          |

Top, right, bottom, left in percentage 0 to 100 in 10 steps.

| Class       | Value         |
| ----------- | ------------- |
| top-p0      | top: 0%;      |
| top-p20     | top: 20%;     |
| top-p100    | top: 100%;    |
| right-p0    | right: 0%;    |
| right-p20   | right: 20%;   |
| right-p100  | right: 100%;  |
| bottom-p0   | bottom: 0%;   |
| bottom-p20  | bottom: 20%;  |
| bottom-p100 | bottom: 100%; |
| left-p0     | left: 0%;     |
| left-p20    | left: 20%;    |
| left-p100   | left: 100%;   |
| etc.        | etc.          |

### For Example:

| Classname                  | Value                                                         |
| -------------------------- | ------------------------------------------------------------- |
| `top-p50 right-p100`       | `top: 50%; right: 100%;`                                      |
| `bottom-p0`                | `bottom: 0%;`                                                 |
| `left-50`                  | `left: 50px;`                                                 |
| `top-p70 left-15 bottom-1` | `padding-right: 10px; margin-top: 15px; margin-bottom: 15px;` |

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

| Class     | Value                       |
| --------- | --------------------------- |
| tac       | text-align: center;         |
| ttc       | text-transform: capitalize; |
| ttu       | text-transform: uppercase;  |
| ttl       | text-transform: lowercase;  |
| tdn       | text-decoration: none;      |
| tdu       | text-decoration: uderline;  |
| td-dash   | text-decoration: dashed;    |
| td-dot    | text-decoration: dotted;    |
| td-double | text-decoration: double;    |
| white     | color: white;               |
| black     | color: black;               |

### Font-Weight

| Class    | Value                |
| -------- | -------------------- |
| fw100    | font-weight: 100;    |
| fw200    | font-weight: 200;    |
| fw300    | font-weight: 300;    |
| fw400    | font-weight: 400;    |
| fw500    | font-weight: 500;    |
| fw600    | font-weight: 600;    |
| fw700    | font-weight: 700;    |
| fw800    | font-weight: 800;    |
| fw900    | font-weight: 900;    |
| fwbold   | font-weight: bold;   |
| fwnormal | font-weight: normal; |

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

### Z-index

Z-index from 0 to 5.

| Class | Value       |
| ----- | ----------- |
| z-0   | z-index: 0; |
| z-1   | z-index: 1; |
| z-2   | z-index: 2; |
| z-3   | z-index: 3; |
| z-4   | z-index: 4; |
| z-5   | z-index: 5; |

### Other

| Class | Value                                                                                                                                                                                  |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| clear | Clears the base styles that the browser sets for: `<a>, <ul>, <li>`. And removed margins for all `<h>` tags. Also for all (\*) other elements: `box-sizing: border-box; outline: none` |
| c-p   | cursor: pointer                                                                                                                                                                        |
