# Dragula

This modules provides the Dragula library, with nothing else than a simple
```hook_library()``` implementation.

Its identifier is ```['dragula', 'dragula']```.

In order to use it, either add it as a dependency in your own library or
attach it this way:

```php
$render = [
  // ... your element info, render array, ...
  '#attached' => [
    'library' => [
      ['dragula', 'dragula'],
    ],
  ],
];
```
