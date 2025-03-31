# Intro

All my cooking recipes shall be stored here.

Recipes are written in [Cooklang](https://cooklang.org/), a markup language specifically designed for cooking recipes.

These recipes are managed with [cooklang-chef](https://github.com/Zheoni/cooklang-chef) by Zheoni which is an extension, and better version, of the original CLI [cook](https://github.com/cooklang/cookcli) by Cooklang.

## example of cook cli

### Read the recipe

```sh
cook recipe read "Root Vegetable Tray Bake.cook"
```

### Create shopping list

```sh
cook shopping-list \
  "Neapolitan Pizza.cook" \
  "Root Vegetable Tray Bake.cook" \
  "Snack Basket I.cook"
```

### Run a server

In directory where you have your recipes run:

```sh
cook server
```

Then open [http://127.0.0.1:9080](http://127.0.0.1:9080) in your browser.

### Automate something

Explore [the docs](https://cooklang.org/cli/help/), which describe how to use CookCLI's automation tools.

### Customize your instance

Add aisle configuration information to the `config/aisle.conf` file to tailor your shopping list experience.




