# `harness.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/lint/rules/harness.test.ts --update-snapshots` to update.

## `js/defaultExportSameBasename`

### `0`

```

 lint/js/defaultExportSameBasename/reject/1/foo.ts:1:24 lint/js/defaultExportSameBasename  FIXABLE
 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The filename and the name of a default function should match.

    export default function test() {}
                            ^^^^

  ℹ The filename should be test.ts or the function name should be foo.

  ℹ Recommended fix

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```
export default function foo() {}

```

### `1`

```

 lint/js/defaultExportSameBasename/reject/2/foo.ts:1:21 lint/js/defaultExportSameBasename  FIXABLE
 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The filename and the name of a default class should match.

    export default class Test {}
                         ^^^^

  ℹ The filename should be Test.ts or the class name should be Foo.

  ℹ Recommended fix

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `1: formatted`

```
export default class Foo {}

```

### `2`

```
✔ No known problems!

```

### `2: formatted`

```
export default function foo() {}

```

### `3`

```
✔ No known problems!

```

### `3: formatted`

```
export default class Foo {}

```

### `4`

```
✔ No known problems!

```

### `4: formatted`

```
export default "rome";

```