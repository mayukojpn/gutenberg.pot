Languages
=========

The generated POT template file from [Gutenberg developing plugin](https://github.com/wordpress/gutenberg). To use this file, replace `/languages/` directory with this repository. To activate translation file, copy `gutenberg-xx.mo` file to `/wp-content/languages/plugins/`. **Override if you find existing `gutenberg-xx.mo` file there.**.

To update POT file, follow instructions from [CONTRIBUTING.md](https://github.com/WordPress/gutenberg/blob/master/CONTRIBUTING.md) to install the project, then run the following command:

```
npm run gettext-strings
```

After the build completes, you'll find a `gutenberg.pot` strings file in this directory.
