# rowlow.layout.horizontal-align

This module adds CSS selectors in order to align block or inline-block elements in HTML

## Install

```
    bower install --save rowlow.layout.horizontal-align
```

## Variables

```
    $rowlow-horizontal-align-namespace // Specific module namespace
```


## Usage

### Setup
```
    /* Set modules namespace (optional) */
    $rowlow-horizontal-align-namespace: "namespace-";

    @import "bower_components/rowlow.layout.horizontal-align/main.scss"
```


### CSS Selector Naming Scheme

```
    .{rowlow-horizontal-align-namespace}horizontal-align--{breakpoint}--{left, center, right}
```

### HTML
```
    <div class="horizontal-align--s--center horizontal-align--m--left"></div>
```
