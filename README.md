# HolyC script

HolyC script is a experimental way to run HolyC in your HTML.

## Usage

**Is not recommended run HolyScript out of a HTTP server, some features dont will work well.**

Import HolyC Script in your dom with the CDN link;

```html
<script
  defer
  crossorigin="anonymous"
  type="module"
  src="https://leonardo.moe/cdn/holy-script-0.0.1.min.js"
></script>
```

After, use the `<holy-script>` to code.

## Example

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script
      defer
      crossorigin="anonymous"
      type="module"
      src="https://holy-js.github.io/HolyScript-0.0.1.min.js"
    ></script>
    <title>HolyC Fibonacci</title>
  </head>

  <body>
    <holy-script>
      U0 Fibonacci() { U32 a = 0, b = 1, c, i; for (i = 0; i < 20; i++) { c = a
      + b; "%d\n" , c; a = b; b = c; } } Fibonacci;
    </holy-script>
  </body>
</html>
```
