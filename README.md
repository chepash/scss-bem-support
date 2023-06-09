# SCSS BEM Highlight

This extension adds TextMate scope to BEM element and modifier which can be useful in syntax highlighting.

> Note: SCSS BEM Highlight is an enhanced fork of the original plugin developed by Jolo Yonaha. For the original project, please visit [Jolo Yonaha's SCSS BEM Support repository](https://github.com/joloyonaha/scss-bem-support). But sadly the original project hasn't received any updates since 2019.

## Preview

![screenshot](https://raw.githubusercontent.com/chepash/scss-bem-support/main/assets/screenshot-v0.1.0.png)

![screenshot](https://raw.githubusercontent.com/chepash/scss-bem-support/main/assets/screenshot-v0.0.5.png)

## BEM – Block Element Modifier

```scss
.block {
  &__element {
  } // bem.support.element.scss
  &--modifier {
  } // bem.support.modifier.scss
  &_modifier {
  } // bem.support.modifier.scss
  &_key_value {
  } // bem.support.modifier.scss
}
```

More info about BEM [here](https://getbem.com/).

## Installation

1. Launch Visual Studio Code.
2. Go to the Extensions view by clicking on the square icon in the sidebar.
3. Search for "SCSS BEM Highlight" in the Marketplace.
4. Click on the "Install" button next to the SCSS BEM Highlight extension.
5. Once installed, the extension will be activated automatically.

## TextMate Scope

Go to `Keyboard Shortcuts` then search for `Developer: Inspect TM Scopes`.

## Changelog

**v0.1.0**

- Add support for `&_modifier` or `&_key_value` notation
- Improve handling of highlighting after single-line comments

**v0.0.6**

- Preserve ampersand tokenization
- Capture dash, underscore, letters and numbers only

**v0.0.5**

- Add `entity.other.attribute-name.class.css` as fallback scope

**v0.0.4**

- Add `bem.support.element.scss` scope
- Add `bem.support.modifier.scss` scope

**v0.0.3**

- Initial release

## Feedback

For comments, questions and suggestions, go [here](https://github.com/chepash/scss-bem-support/issues).

## Contributors

- Danny McGee - [@dannymcgee](https://github.com/dannymcgee)
- Pavel Cherdantsev - [@chepash](https://github.com/chepash)

## License

© 2019 [Jolo Yonaha](https://github.com/joloyonaha)

[MIT License](https://github.com/chepash/scss-bem-support/blob/main/LICENSE)
