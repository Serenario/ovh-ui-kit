# oui-tabs

<component-status cx-design="partial" ux="rc"></component-status>

oui-tabs is a package which provides styles for the tabs component.

## Installation

```less
  @import 'oui-tabs/tabs';
```

## Usage

```html:preview
<ul class="oui-tabs">
  <li class="oui-tabs__item">
    <button class="oui-tabs__button oui-tabs__button_active">
      First tab
    </button>
  </li>
  <li class="oui-tabs__item">
    <button class="oui-tabs__button" disabled>
      Disabled tab
    </button>
  </li>
  <li class="oui-tabs__item">
    <a class="oui-tabs__button" href="https://ovh.com">
      External link
    </a>
  </li>
</ul>
```