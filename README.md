<p align="center">
    <img alt="elementid-logo" src="./logo/layout-css-modules.jpg"/>
</p>

# Layout CSS Modules

Layout CSS Modules is a CSS grid system based on Bootstrap's grid, but with the added benefits of CSS modules. With this library, you can create responsive layouts for your web applications with ease.

## Installation

You can install Layout CSS Modules using npm:

```bash
npm install layout-css-modules
```

## Usage

```astro
---
import { container, row, col12, colXL4 } from "layout-css-modules/index.module.css";
---

<div class:list={[container]}>
	<div class:list={[row]}>
		<div class:list={[col12, colXL4]}>Column</div>
		<div class:list={[col12, colXL4]}>Column</div>
		<div class:list={[col12, colXL4]}>Column</div>
	</div>
</div>

```

## License

Layout CSS Modules is licensed under the [MIT](./LICENSE) License.
