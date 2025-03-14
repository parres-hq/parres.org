# Parres

This is the Parres website. It's simple. On purpose.

## Development

We use tailwindcss for styles, and the tailwindcss CLI to build our styles.

To dynamically update the styles as you develop you can run:

```sh
bunx @tailwindcss/cli -i ./input.css -o ./output.css --watch
```

Before pushing minifiy and optimize the output with:

```sh
bunx @tailwindcss/cli -i ./input.css -o ./output.css --minify
```
