# Snippets Niten Tokens

[![license](https://img.shields.io/github/license/getninjas/niten-vscode-snippets)](https://github.com/getninjas/niten-vscode-snippets/blob/master/LICENSE)
[![version](https://img.shields.io/visual-studio-marketplace/v/getninjas.niten-tokens-snippets)](https://marketplace.visualstudio.com/items?itemName=getninjas.niten-tokens-snippets)

Snippets for [Niten Tokens Design System](https://github.com/getninjas/niten-tokens/)

## Usage

Type part of a snippet, press `nt`, and the snippet unfolds.

![Usage](images/usage.gif)

## Snippets

### Border

#### Radius

| Snippet            | Variant                           | Value                                       |
|--------------------|-----------------------------------|---------------------------------------------|
| ntBorderRadius     | none [`0`]                        | $size-border-radius-none                    |
|                    | small [`4px`]                     | $size-border-radius-s                       |
|                    | medium [`8px`]                    | $size-border-radius-m                       |
|                    | large [`16px`]                    | $size-border-radius-large                   |
|                    | circle [`50%`]                    | $size-border-radius-circle                  |
|                    | pill [`160px`]                    | $size-border-radius-pill                    |

#### Style

| Snippet            | Variant                           | Value                                       |
|--------------------|-----------------------------------|---------------------------------------------|
| ntborderStyle      | default [`solid`]                 | $border-style-default                       |

#### Width

| Snippet            | Variant                           | Value                                       |
|--------------------|-----------------------------------|---------------------------------------------|
| ntborderWidth      | none [`0`]                        | $size-border-width-none                     |
|                    | thin [`1px`]                      | $size-border-width-thin                     |
|                    | thick [`2px`]                     | $size-border-width-thick                    |

### Colors

#### Brand

| Snippet            | Variant                           | Value                                       |
|--------------------|-----------------------------------|---------------------------------------------|
| ntColorBrand       | firstExtraDark [`#212121`]        | $color-brand-first-extra-dark               |
|                    | firstDark [`#212121`]             | $color-brand-first-dark                     |
|                    | firstMedium [`#575757`]           | $color-brand-first-medium                   |
|                    | firstLight [`#fff`]               | $color-brand-first-light                    |
|                    | secondExtraDark [`#615600`]       | $color-brand-first-second-extra-dark        |
|                    | secondDark [`#ffea52`]            | $color-brand-first-second-dark              |
|                    | secondMedium [`#fff399`]          | $color-brand-first-second-medium            |
|                    | secondLight [`#fffce6`]           | $color-brand-first-second-light             |

#### Interface

| Snippet            | Variant                           | Value                                       |
|--------------------|-----------------------------------|---------------------------------------------|
| ntColorInterface   | positiveExtraDark [`#006513`]     | $color-interface-positive-extra-dark        |
|                    | positiveDark [`#25a159`]          | $color-interface-positive-dark              |
|                    | positiveMedium [`#a0e9be`]        | $color-interface-positive-medium            |
|                    | positiveLight [`#eafaf1`]         | $color-interface-positive-light             |
|                    | alertExtraDark [`#d78e00`]        | $color-interface-alert-extra-dark           |
|                    | alertDark [`#f6ba50`]             | $color-interface-alert-dark                 |
|                    | alertMedium [`#fff085`]           | $color-interface-alert-medium               |
|                    | alertLight [`#fffce6`]            | $color-interface-alert-light                |
|                    | negativeExtraDark [`#b40300`]     | $color-interface-negative-extra-dark        |
|                    | negativeDark [`#f26565`]          | $color-interface-negative-dark              |
|                    | negativeMedium [`#f49999`]        | $color-interface-negative-medium            |
|                    | negativeLight [`#fdecec`]         | $color-interface-negative-light             |
|                    | highlightExtraDark [`#5319a9`]    | $color-interface-highlight-extra-dark       |
|                    | highlightDark [`#9a63ee`]         | $color-interface-highlight-dark             |
|                    | highlightMedium [`#c8a3ff`]       | $color-interface-highlight-medium           |
|                    | highlightLight [`#f3ebff`]        | $color-interface-highlight-light            |
|                    | actionExtraDark [`#195ca9`]       | $color-interface-action-extra-dark          |
|                    | actionDark [`#009ded`]            | $color-interface-action-dark                |
|                    | actionMedium [`#7ad6ff`]          | $color-interface-action-medium              |
|                    | actionLight [`#e5f7ff`]           | $color-interface-action-light               |
|                    | actionLight [`#e5f7ff`]           | $color-interface-action-light               |

### Font

#### Family

| Snippet            | Variant                           | Value                                       |
|--------------------|-----------------------------------|---------------------------------------------|
| ntFontFamily       | default ['Source Sans Pro']       | $font-family-default                        |

#### Sizes

| Snippet            | Variant                           | Value                                       |
|--------------------|-----------------------------------|---------------------------------------------|
| ntFontSize         | xxs [`14px`]                      | $size-font-xxs                              |
|                    | xs  [`16px`]                      | $size-font-xs                               |
|                    | s   [`20px`]                      | $size-font-s                                |
|                    | m   [`24px`]                      | $size-font-m                                |
|                    | l   [`32px`]                      | $size-font-l                                |
|                    | xl  [`48px`]                      | $size-font-xl                               |
|                    | xxl [`60px`]                      | $size-font-xxl                              |

#### Style

| Snippet            | Variant                           | Value                                       |
|--------------------|-----------------------------------|---------------------------------------------|
| ntFontQuote        | quote [italic]                    | $font-style-quote                           |

#### Weight

| Snippet            | Variant                           | Value                                       |
|--------------------|-----------------------------------|---------------------------------------------|
| ntFontWeight       | light [`300`]                     | $font-style-weight-light                    |
|                    | medium  [`400`]                   | $font-style-weight-medium                   |
|                    | bold   [`600`]                    | $font-style-weight-bold                     |

### Line Height

| Snippet            | Variant                           | Value                                       |
|--------------------|-----------------------------------|---------------------------------------------|
| ntLineHeight       | equal [`1`]                       | $size-line-height-equal                     |
|                    | xxs [`22px`]                      | $size-line-height-xxs                       |
|                    | xs [`24px`]                       | $size-line-height-xs                        |
|                    | s [`28px`]                        | $size-line-height-s                         |
|                    | m [`32px`]                        | $size-line-height-m                         |
|                    | l [`40px`]                        | $size-line-height-l                         |
|                    | xl [`56px`]                       | $size-line-height-xl                        |
|                    | xxl [`68px`]                      | $size-line-height-xxl                       |

### Opacity

| Snippet            | Variant                           | Value                                       |
|--------------------|-----------------------------------|---------------------------------------------|
| ntOpacity          | translucent [`.35`]               | $opacity-translucent                        |
|                    | opaque [`.6`]                     | $opacity-opaque                             |

### Shadows

| Snippet            | Variant                           | Value                                       |
|--------------------|-----------------------------------|---------------------------------------------|
| ntShadow           | topLevel-1                        | $shadow-top-level-1                         |
|                    | topLevel-2                        | $shadow-top-level-2                         |
|                    | topLevel-3                        | $shadow-top-level-3                         |
|                    | bottomLevel-1                     | $shadow-bottom-level-1                      |
|                    | bottomLevel-2                     | $shadow-bottom-level-2                      |
|                    | bottomLevel-3                     | $shadow-bottom-level-3                      |

### Spacing

| Snippet            | Variant                           | Value                                       |
|--------------------|-----------------------------------|---------------------------------------------|
| ntShadow, ntMargin, ntPadding | xxxs [`8px`] | $size-spacing-xxxs                          |
|                    | xxs  [`12px`]                     | $size-spacing-xxs                           |
|                    | xs   [`16px`]                     | $size-spacing-xs                            |
|                    | s    [`24px`]                     | $size-spacing-s                             |
|                    | m    [`36px`]                     | $size-spacing-m                             |
|                    | l    [`48px`]                     | $size-spacing-l                             |
|                    | xl   [`48px`]                     | $size-spacing-xl                            |
|                    | xxl  [`48px`]                     | $size-spacing-xxl                           |
|                    | xxxl [`48px`]                     | $size-spacing-xxxl                          |

## Known Issues

[GitHub Issues](https://github.com/getninjas/niten-vscode-snippets/issues)

## Release Notes

Users appreciate release notes as you update your extension.

### 0.1.0

- Doc Improvements
- Fix line-height description

### 0.0.1

- Added snippets to use Niten Tokens

## License

[MIT](https://github.com/getninjas/niten-vscode-snippets/blob/master/LICENSE)
