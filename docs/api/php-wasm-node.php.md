<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## PHP class

<b>Signature:</b>

```typescript
class PHP implements WithPHPIniBindings, WithFilesystem, WithNodeFilesystem, WithCLI, WithRun
```

<b>Implements:</b> [WithPHPIniBindings](./php-wasm-node.withphpinibindings.md)<!-- -->, [WithFilesystem](./php-wasm-node.withfilesystem.md)<!-- -->, [WithNodeFilesystem](./php-wasm-node.withnodefilesystem.md)<!-- -->, [WithCLI](./php-wasm-node.withcli.md)<!-- -->, [WithRun](./php-wasm-node.withrun.md)

## Remarks

The constructor for this class is marked as internal. Third-party code should not call the constructor directly or create subclasses that extend the `PHP` class.

An environment-agnostic wrapper around the Emscripten PHP runtime
that abstracts the super low-level API and provides a more convenient
higher-level API.

It exposes a minimal set of methods to run PHP scripts and to
interact with the PHP filesystem.

## Methods

### addServerGlobalEntry<!-- -->(<!-- -->key<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->, value<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### cli<!-- -->(<!-- -->argv<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->[]<!-- -->)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[number](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->&gt;

### fileExists<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [boolean](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)

### initializeRuntime<!-- -->(<!-- -->runtimeId<!-- -->: [PHPRuntimeId](./php-wasm-node.phpruntimeid.md)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### isDir<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [boolean](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)

### listFiles<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->[]

### mkdirTree<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### mount<!-- -->(<!-- -->settings<!-- -->: [MountSettings](./php-wasm-node.mountsettings.md)<!-- -->, path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### readFileAsBuffer<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [Uint8Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint8Array)

### readFileAsText<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)

### run<!-- -->(<!-- -->request?<!-- -->: [PHPRequest](./php-wasm-node.phprequest.md)<!-- -->)<!-- -->: [PHPResponse](./php-wasm-node.phpresponse.md)

-   `request` – Optional.

### setPhpIniEntry<!-- -->(<!-- -->key<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->, value<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### setPhpIniPath<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### setSkipShebang<!-- -->(<!-- -->shouldSkip<!-- -->: [boolean](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### unlink<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### writeFile<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->, data<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->|[Uint8Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint8Array)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)