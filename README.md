# Markdown Style

> Based on [github-markdown-css](https://github.com/sindresorhus/github-markdown-css).

## Install
```bash
npm i mark-down-style
```

## Supported sass variables
```scss
/* the container's className */
$containerClassName:          md-style !default;

/* heading font size */
$base-font-size:              12px !default;
$h1-font-size:                $base-font-size + 2 * 6  !default;
$h2-font-size:                $base-font-size + 2 * 5 !default;
$h3-font-size:                $base-font-size + 2 * 4 !default;
$h4-font-size:                $base-font-size + 2 * 3 !default;
$h5-font-size:                $base-font-size + 2 * 2 !default;
$h6-font-size:                $base-font-size + 2 * 1 !default;

/* pre background color */
$pre-bg-color:                #333 !default;
$pre-shadow-opacity:          50% !default;
$pre-font-size:               $base-font-size !default;

/* inline `code`  */
$code-font-color:             #b8341e !default;

```

## Supported CSS 3 variables
```css
--pre-bg-color: #{$pre-bg-color};
--pre-shadow-opacity: #{$pre-shadow-opacity};
--pre-font-size: #{$pre-font-size};
--code-font-color: #{$code-font-color};
```

You can rewrite css 3 variables like below:
```css
.md-style {
  --pre-bg-color: #eee !important;
  --pre-shadow-opacity: 10% !important;
  --code-font-size: 13px !important;
  --code-font-color: blue !important;
}
```