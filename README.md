# Cheese toast

> Straightforward toast with no dependencies

## Usage

Import `cheese-toast` by including the following script tag in your HTML:

```html
<script src="https://unpkg.com/cheese-toast"></script>
```

The factory function `CheeseToast` is now available to construct new toast instances. If you wish to close the popup programmatically, you can call the `hide` method on the instance.

```js
new CheeseToast({
  text: 'Success!',
  className: 'toast', // handy for styling
})
```

## Contributing

This project is open to and encourages contributions! Feel free to discuss any bug fixes/features in the [issues](https://github.com/shwilliam/cheese-toast/issues). If you wish to work on this project:

1. Fork [this project](https://github.com/shwilliam/cheese-toast)
2. Create your feature branch (`git checkout -b new-feature-branch`)
3. Commit your changes (`git commit -am 'add new feature'`)
4. Push to the branch (`git push origin new-feature-branch`)
5. [Submit a pull request!](https://github.com/shwilliam/cheese-toast/pull/new/master)
