# oui-tabs

<component-status cx-design="partial" ux="rc"></component-status>

oui-tabs is a package which provides styles for the tabs component.

## Installation

```less
  @import 'oui-tabs/tabs';
```

## Usage

```html:preview
<div class="oui-tabs">
  <ul class="oui-tabs__items">
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
</div>
```

```html:preview
<div class="oui-tabs">
  <ul class="oui-tabs__items oui-tabs__items_with-content">
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
  <div class="oui-tabs__content">
    Put some content here
  </div>
</div>
```