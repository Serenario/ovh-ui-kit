# oui-select

<component-status cx-design="complete" ux="rc"></component-status>

## Installation

```less
  @import 'oui-select/select';
```

## Usage

```html:preview
<label class="oui-select">
  <select id="select" name="select" class="oui-select__input">
    <option value="Option 1">Option 1</option>
    <option value="Option 2">Option 2</option>
    <option value="Option 3">Option 3</option>
  </select>
  <i class="oui-icon oui-icon-chevron-down" aria-hidden="true"></i>
</label>

<label class="oui-select">
  <select id="select-disabled" name="select-disabled" class="oui-select__input" disabled>
    <option value="Option 1">Option 1</option>
    <option value="Option 2">Option 2</option>
    <option value="Option 3">Option 3</option>
  </select>
  <i class="oui-icon oui-icon-chevron-down" aria-hidden="true"></i>
</label>

<label class="oui-select oui-select_error">
  <select id="select-error" name="select-error" class="oui-select__input">
    <option value="Option 1">Option 1</option>
    <option value="Option 2">Option 2</option>
    <option value="Option 3">Option 3</option>
  </select>
  <i class="oui-icon oui-icon-chevron-down" aria-hidden="true"></i>
</label>
```

### Inline select

```html:preview
<label class="oui-select oui-select_inline">
  <select id="select-inline" name="select-inline" class="oui-select__input">
    <option value="Option 1">Option 1</option>
    <option value="Option 2">Option 2</option>
    <option value="Option 3">Option 3</option>
  </select>
  <i class="oui-icon oui-icon-chevron-down" aria-hidden="true"></i>
</label>
```

### Sizes

```html:preview
<label class="oui-select oui-select_xs">
  <select class="oui-select__input">
    <option>XS</option>
    <option value="Option 1">Option 1</option>
    <option value="Option 2">Option 2</option>
    <option value="Option 3">Option 3</option>
  </select>
  <i class="oui-icon oui-icon-chevron-down" aria-hidden="true"></i>
</label>
<label class="oui-select oui-select_s">
  <select class="oui-select__input">
    <option>S</option>
    <option value="Option 1">Option 1</option>
    <option value="Option 2">Option 2</option>
    <option value="Option 3">Option 3</option>
  </select>
  <i class="oui-icon oui-icon-chevron-down" aria-hidden="true"></i>
</label>
<label class="oui-select oui-select_m">
  <select class="oui-select__input">
    <option>M</option>
    <option value="Option 1">Option 1</option>
    <option value="Option 2">Option 2</option>
    <option value="Option 3">Option 3</option>
  </select>
  <i class="oui-icon oui-icon-chevron-down" aria-hidden="true"></i>
</label>
<label class="oui-select oui-select_l">
  <select class="oui-select__input">
    <option>L</option>
    <option value="Option 1">Option 1</option>
    <option value="Option 2">Option 2</option>
    <option value="Option 3">Option 3</option>
  </select>
  <i class="oui-icon oui-icon-chevron-down" aria-hidden="true"></i>
</label>
<label class="oui-select oui-select_xl">
  <select class="oui-select__input">
    <option>XL</option>
    <option value="Option 1">Option 1</option>
    <option value="Option 2">Option 2</option>
    <option value="Option 3">Option 3</option>
  </select>
  <i class="oui-icon oui-icon-chevron-down" aria-hidden="true"></i>
</label>
```
