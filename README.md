# colors
--color-variables for windows-ui.


| Color Name | Light | Dark |
|---|---|---|
| `--PrimaryColor` | ![#0078d7](https://placehold.co/15x15/0078d7/0078d7.png) `#0078D7` | ![#0078d7](https://placehold.co/15x15/0078d7/0078d7.png) `#0078D7` |
| `--PrimaryColorLight` | ![#47aeff](https://placehold.co/15x15/47aeff/47aeff.png) `#F03C15` | ![#47aeff](https://placehold.co/15x15/47aeff/47aeff.png) `#F03C15` |
| `--color-primary-adaptive` | ![#0078d7](https://placehold.co/15x15/0078d7/0078d7.png) `var(--PrimaryColor)` | ![#47aeff](https://placehold.co/15x15/47aeff/47aeff.png)  `var(--PrimaryColorLight)` |
| `--color-scheme-absolute` | ![#ffffff](https://placehold.co/15x15/eeeeee/eeeeee.png) `#FFFFFF` | ![#000000](https://placehold.co/15x15/000000/000000.png) `#000000` |
| `--color-danger-default` | ![#C50500](https://placehold.co/15x15/C50500/C50500.png) `#F03C15` | ![#FF99A3](https://placehold.co/15x15/FF99A3/FF99A3.png) `#FF99A3` |
| `--color-success-default` | ![#2C8B2C](https://placehold.co/15x15/2C8B2C/2C8B2C.png) `#2C8B2C` | ![#6ACB5D](https://placehold.co/15x15/6ACB5D/6ACB5D.png) `#6ACB5D` |
| `--color-background-default` | ![#ffffff](https://placehold.co/15x15/eeeeee/eeeeee.png) `#FFFFFF` | ![#111111](https://placehold.co/15x15/111111/111111.png) `#111111` |
| `--color-button-default` | ![#e9e9e9](https://placehold.co/15x15/e9e9e9/e9e9e9.png) `#E9E9E9` | ![#484848](https://placehold.co/15x15/484848/484848.png) `#484848` |
| `--color-button-hover` | ![#666666](https://placehold.co/15x15/666666/666666.png) `#666666` | ![#999999](https://placehold.co/15x15/999999/999999.png) `#999999` |
| `--color-day-primary-night-grey` | ![#0078d7](https://placehold.co/15x15/0078d7/0078d7.png) `var(--PrimaryColor)` | ![#FFFFFF](https://placehold.co/15x15/403E41/403E41.png) `#403E41` |
| `--color-day-primary-night-white` | ![#0078d7](https://placehold.co/15x15/0078d7/0078d7.png) `var(--PrimaryColor)` | ![#FFFFFF](https://placehold.co/15x15/eeeeee/eeeeee.png) `#FFFFFF` |
| `--color-foreground-default` | ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) `#F03C15` | ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) `#F03C15` |
| `--color-foreground-default` | ![#ffffff](https://placehold.co/15x15/eeeeee/eeeeee.png) `#FFFFFF` | ![#2B2B2B](https://placehold.co/15x15/2B2B2B/2B2B2B.png) `#2B2B2B` |
| `--color-grey-light` | ![#0078d7](https://placehold.co/15x15/DDDDDD/DDDDDD.png) `#EEEEEE` | ![#444444](https://placehold.co/15x15/444444/444444.png) `#444444` |
| `--color-grey-light-alpha` | ![#EEEEEED1](https://placehold.co/15x15/EEEEEE/EEEEEE.png) `#EEEEEED1` | ![#44444477](https://placehold.co/15x15/444444/444444.png) `#44444477` |
| `--color-link-bg-active` | ![#D8D8D8](https://placehold.co/15x15/D8D8D8/D8D8D8.png) `#D8D8D8` | ![#262626](https://placehold.co/15x15/262626/262626.png) `#262626` |
| `--color-link-bg-hover` | ![#E8E8E8](https://placehold.co/15x15/E8E8E8/E8E8E8.png) `#E8E8E8` | ![#2D2D2D](https://placehold.co/15x15/2D2D2D/2D2D2D.png) `#2D2D2D` |
| `--color-navbar-bg-default` | ![#F3F3F3](https://placehold.co/15x15/F3F3F3/F3F3F3.png) `#F3F3F3` | ![#202020](https://placehold.co/15x15/202020/202020.png) `#202020` |
| `--color-text-default` | ![#000000](https://placehold.co/15x15/000000/000000.png) `#000000` | ![#0078d7](https://placehold.co/15x15/eeeeee/eeeeee.png) `#FFFFFF` |

## CSS Code
<pre>
  :root {
  --PrimaryColor: #0078d7;
  --PrimaryColorLight: #47aeff;
  --color-primary-adaptive: #0078d7;
  --color-primary-adaptive-light: var(--PrimaryColorLight);
  --color-scheme-absolute-light: #ffffff;
  --color-scheme-absolute-dark: #000000;
  --color-danger-default-light: #C50500;
  --color-danger-default-dark: #FF99A3;
  --color-success-default-light: #2C8B2C;
  --color-success-default-dark: #6ACB5D;
  --color-background-default-light: #ffffff;
  --color-background-default-dark: #111111;
  --color-button-default-light: #e9e9e9;
  --color-button-default-dark: #484848;
  --color-button-hover-light: #666666;
  --color-button-hover-dark: #999999;
  --color-day-primary-night-grey-light: #0078d7;
  --color-day-primary-night-grey-dark: #403E41;
  --color-day-primary-night-white-light: #0078d7;
  --color-day-primary-night-white-dark: #FFFFFF;
  --color-foreground-default-light: #f03c15;
  --color-foreground-default-dark: #2B2B2B;
  --color-grey-light-light: #EEEEEE;
  --color-grey-light-dark: #444444;
  --color-grey-light-alpha-light: #EEEEEED1;
  --color-grey-light-alpha-dark: #44444477;
  --color-link-bg-active-light: #D8D8D8;
  --color-link-bg-active-dark: #262626;
  --color-link-bg-hover-light: #E8E8E8;
  --color-link-bg-hover-dark: #2D2D2D;
  --color-navbar-bg-default-light: #F3F3F3;
  --color-navbar-bg-default-dark: #202020;
  --color-text-default-light: #000000;
  --color-text-default-dark: #0078d7;
}
</pre>
