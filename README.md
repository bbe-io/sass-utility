# Sass Utility

**Sass utility class generator**

## Usage

### Spacers

```html
<!-- Div spacers -->
<div class="spacer-xs"></div>
<div class="spacer-sm"></div>
<div class="spacer-md"></div>
<div class="spacer-lg"></div>
<div class="spacer-xl"></div>

<!-- Margin spacers -->
<!-- Where {size} can be 0, xs, sm, md, lg, or xl -->
<div class="m-a-{size}"></div> <!-- All sides -->
<div class="m-t-{size}"></div> <!-- Top -->
<div class="m-r-{size}"></div> <!-- Right -->
<div class="m-b-{size}"></div> <!-- Bottom -->
<div class="m-l-{size}"></div> <!-- Left -->
<div class="m-x-{size}"></div> <!-- Left and Right -->
<div class="m-y-{size}"></div> <!-- Top and Bottom -->

<!-- Padding spacers -->
<!-- Where {size} can be 0, xs, sm, md, lg, or xl -->
<div class="p-a-{size}"></div> <!-- All sides -->
<div class="p-t-{size}"></div> <!-- Top -->
<div class="p-r-{size}"></div> <!-- Right -->
<div class="p-b-{size}"></div> <!-- Bottom -->
<div class="p-l-{size}"></div> <!-- Left -->
<div class="p-x-{size}"></div> <!-- Left and Right -->
<div class="p-y-{size}"></div> <!-- Top and Bottom -->
```

### Colors

```scss
$colors: (
    'white': #ffffff
);
```

```html
<p class="color-white">Styled Text</div>
<p class="outline-color-white">Styled Text</div>
<p class="background-color-white">Styled Text</div>

<p class="border-color-white">Styled Text</div>
<p class="border-top-color-white">Styled Text</div>
<p class="border-left-color-white">Styled Text</div>
<p class="border-right-color-white">Styled Text</div>
<p class="border-bottom-color-white">Styled Text</div>

<p class="text-decoration-color-white">Styled Text</div>
```

### Fonts

```html
<p class="text-transform-none">Styled Text</div>
<p class="text-transform-uppercase">Styled Text</div>
<p class="text-transform-lowercase">Styled Text</div>

<p class="font-weight-thin">Styled Text</div>
<p class="font-weight-light">Styled Text</div>
<p class="font-weight-book">Styled Text</div>
<p class="font-weight-normal">Styled Text</div>
<p class="font-weight-medium">Styled Text</div>
<p class="font-weight-semibold">Styled Text</div>
<p class="font-weight-bold">Styled Text</div>
<p class="font-weight-extrabold">Styled Text</div>
<p class="font-weight-black">Styled Text</div>

<p class="letter-spacing-xs">Styled Text</div>
<p class="letter-spacing-sm">Styled Text</div>
<p class="letter-spacing-md">Styled Text</div>
<p class="letter-spacing-lg">Styled Text</div>
<p class="letter-spacing-lg">Styled Text</div>
```