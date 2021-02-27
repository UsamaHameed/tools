# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/formatter/index.test.ts --update-snapshots` to update.

## `css > namespace-prefix`

### `Diagnostics`

```

```

### `Input`

```css
*|a {

}

|a {

}

namespace|a {

}

[*|attr = value] {

}

```

### `Output`

```css
*|a {
}

|a {
}

namespace|a {
}

[*|attr=value] {
}

```