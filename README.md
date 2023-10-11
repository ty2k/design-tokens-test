This repo holds an example sd-transforms token transformation build using the [Full Example](https://github.com/tokens-studio/sd-transforms#full-example) code from the [tokens-studio/sd-transforms repo](https://github.com/tokens-studio/sd-transforms).

This code throws an error using the included `tokens.json` file, which is exported from Tokens Studio for Figma with a Pro license.

I find if I replace add `typography.` manually to all of the composite tokens in `tokens.json`, the transformation works as expected.

Here's the output I'm getting:

```
$ npm run build

> design-tokens-test@0.0.1 build
> node build-output.js

Warning: could not resolve reference {fontWeights.regular}
Warning: could not resolve reference {fontWeights.regular}
Warning: could not resolve reference {fontWeights.regular}
Warning: could not resolve reference {fontWeights.regular}
Warning: could not resolve reference {fontWeights.regular}
Warning: could not resolve reference {fontWeights.regular}
Warning: could not resolve reference {fontWeights.regular}
Warning: could not resolve reference {fontWeights.regular}
Warning: could not resolve reference {fontWeights.regular}
Warning: could not resolve reference {fontWeights.bold}
Warning: could not resolve reference {fontWeights.bold}
Warning: could not resolve reference {fontWeights.bold}
Warning: could not resolve reference {fontWeights.bold}
Warning: could not resolve reference {fontWeights.bold}
Warning: could not resolve reference {fontWeights.bold}
Warning: could not resolve reference {fontWeights.bold}
Warning: could not resolve reference {fontWeights.bold}
Warning: could not resolve reference {fontWeights.regular}
Warning: could not resolve reference {fontWeights.italic}
Warning: could not resolve reference {fontWeights.italic}
Warning: could not resolve reference {fontWeights.italic}
Warning: could not resolve reference {fontWeights.italic}
Warning: could not resolve reference {fontWeights.italic}
Warning: could not resolve reference {fontWeights.italic}
Warning: could not resolve reference {fontWeights.italic}
Warning: could not resolve reference {fontWeights.italic}
Warning: could not resolve reference {fontWeights.italic}

js

Property Reference Errors:
Reference doesn't exist: typography.regular.label.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.regular.label.value.fontWeight tries to reference fontWeights.regular, which is not defined
Reference doesn't exist: typography.regular.label.value.lineHeight tries to reference lineHeights.xxdense, which is not defined
Reference doesn't exist: typography.regular.label.value.fontSize tries to reference fontSize.label, which is not defined
Reference doesn't exist: typography.regular.label.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.regular.label.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.regular.label.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.regular.label.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.regular.label.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.regular.body.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.regular.body.value.fontWeight tries to reference fontWeights.regular, which is not defined
Reference doesn't exist: typography.regular.body.value.lineHeight tries to reference lineHeights.xdense, which is not defined
Reference doesn't exist: typography.regular.body.value.fontSize tries to reference fontSize.body, which is not defined
Reference doesn't exist: typography.regular.body.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.regular.body.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.regular.body.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.regular.body.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.regular.body.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.regular.largeBody.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.regular.largeBody.value.fontWeight tries to reference fontWeights.regular, which is not defined
Reference doesn't exist: typography.regular.largeBody.value.lineHeight tries to reference lineHeights.dense, which is not defined
Reference doesn't exist: typography.regular.largeBody.value.fontSize tries to reference fontSize.largeBody, which is not defined
Reference doesn't exist: typography.regular.largeBody.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.regular.largeBody.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.regular.largeBody.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.regular.largeBody.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.regular.largeBody.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.regular.H5.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.regular.H5.value.fontWeight tries to reference fontWeights.regular, which is not defined
Reference doesn't exist: typography.regular.H5.value.lineHeight tries to reference lineHeights.regular, which is not defined
Reference doesn't exist: typography.regular.H5.value.fontSize tries to reference fontSize.H5, which is not defined
Reference doesn't exist: typography.regular.H5.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.regular.H5.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.regular.H5.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.regular.H5.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.regular.H5.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.regular.H4.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.regular.H4.value.fontWeight tries to reference fontWeights.regular, which is not defined
Reference doesn't exist: typography.regular.H4.value.lineHeight tries to reference lineHeights.sparse, which is not defined
Reference doesn't exist: typography.regular.H4.value.fontSize tries to reference fontSize.H4, which is not defined
Reference doesn't exist: typography.regular.H4.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.regular.H4.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.regular.H4.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.regular.H4.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.regular.H4.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.regular.H3.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.regular.H3.value.fontWeight tries to reference fontWeights.regular, which is not defined
Reference doesn't exist: typography.regular.H3.value.lineHeight tries to reference lineHeights.xsparse, which is not defined
Reference doesn't exist: typography.regular.H3.value.fontSize tries to reference fontSize.H3, which is not defined
Reference doesn't exist: typography.regular.H3.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.regular.H3.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.regular.H3.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.regular.H3.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.regular.H3.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.regular.H2.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.regular.H2.value.fontWeight tries to reference fontWeights.regular, which is not defined
Reference doesn't exist: typography.regular.H2.value.lineHeight tries to reference lineHeights.xxsparse, which is not defined
Reference doesn't exist: typography.regular.H2.value.fontSize tries to reference fontSize.H2, which is not defined
Reference doesn't exist: typography.regular.H2.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.regular.H2.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.regular.H2.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.regular.H2.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.regular.H2.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.regular.H1.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.regular.H1.value.fontWeight tries to reference fontWeights.regular, which is not defined
Reference doesn't exist: typography.regular.H1.value.lineHeight tries to reference lineHeights.xsparse, which is not defined
Reference doesn't exist: typography.regular.H1.value.fontSize tries to reference fontSize.H1, which is not defined
Reference doesn't exist: typography.regular.H1.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.regular.H1.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.regular.H1.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.regular.H1.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.regular.H1.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.regular.display.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.regular.display.value.fontWeight tries to reference fontWeights.regular, which is not defined
Reference doesn't exist: typography.regular.display.value.lineHeight tries to reference lineHeights.auto, which is not defined
Reference doesn't exist: typography.regular.display.value.fontSize tries to reference fontSize.display, which is not defined
Reference doesn't exist: typography.regular.display.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.regular.display.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.regular.display.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.regular.display.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.regular.display.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.bold.label.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.bold.label.value.fontWeight tries to reference fontWeights.bold, which is not defined
Reference doesn't exist: typography.bold.label.value.lineHeight tries to reference lineHeights.xxdense, which is not defined
Reference doesn't exist: typography.bold.label.value.fontSize tries to reference fontSize.label, which is not defined
Reference doesn't exist: typography.bold.label.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.bold.label.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.bold.label.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.bold.label.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.bold.label.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.bold.body.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.bold.body.value.fontWeight tries to reference fontWeights.bold, which is not defined
Reference doesn't exist: typography.bold.body.value.lineHeight tries to reference lineHeights.xdense, which is not defined
Reference doesn't exist: typography.bold.body.value.fontSize tries to reference fontSize.body, which is not defined
Reference doesn't exist: typography.bold.body.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.bold.body.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.bold.body.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.bold.body.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.bold.body.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.bold.largeBody.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.bold.largeBody.value.fontWeight tries to reference fontWeights.bold, which is not defined
Reference doesn't exist: typography.bold.largeBody.value.lineHeight tries to reference lineHeights.dense, which is not defined
Reference doesn't exist: typography.bold.largeBody.value.fontSize tries to reference fontSize.largeBody, which is not defined
Reference doesn't exist: typography.bold.largeBody.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.bold.largeBody.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.bold.largeBody.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.bold.largeBody.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.bold.largeBody.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.bold.H5.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.bold.H5.value.fontWeight tries to reference fontWeights.bold, which is not defined
Reference doesn't exist: typography.bold.H5.value.lineHeight tries to reference lineHeights.regular, which is not defined
Reference doesn't exist: typography.bold.H5.value.fontSize tries to reference fontSize.H5, which is not defined
Reference doesn't exist: typography.bold.H5.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.bold.H5.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.bold.H5.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.bold.H5.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.bold.H5.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.bold.H4.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.bold.H4.value.fontWeight tries to reference fontWeights.bold, which is not defined
Reference doesn't exist: typography.bold.H4.value.lineHeight tries to reference lineHeights.sparse, which is not defined
Reference doesn't exist: typography.bold.H4.value.fontSize tries to reference fontSize.H4, which is not defined
Reference doesn't exist: typography.bold.H4.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.bold.H4.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.bold.H4.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.bold.H4.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.bold.H4.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.bold.H3.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.bold.H3.value.fontWeight tries to reference fontWeights.bold, which is not defined
Reference doesn't exist: typography.bold.H3.value.lineHeight tries to reference lineHeights.xxsparse, which is not defined
Reference doesn't exist: typography.bold.H3.value.fontSize tries to reference fontSize.H3, which is not defined
Reference doesn't exist: typography.bold.H3.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.bold.H3.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.bold.H3.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.bold.H3.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.bold.H3.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.bold.H2.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.bold.H2.value.fontWeight tries to reference fontWeights.bold, which is not defined
Reference doesn't exist: typography.bold.H2.value.lineHeight tries to reference lineHeights.xsparse, which is not defined
Reference doesn't exist: typography.bold.H2.value.fontSize tries to reference fontSize.H2, which is not defined
Reference doesn't exist: typography.bold.H2.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.bold.H2.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.bold.H2.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.bold.H2.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.bold.H2.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.bold.H1.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.bold.H1.value.fontWeight tries to reference fontWeights.bold, which is not defined
Reference doesn't exist: typography.bold.H1.value.lineHeight tries to reference lineHeights.auto, which is not defined
Reference doesn't exist: typography.bold.H1.value.fontSize tries to reference fontSize.H1, which is not defined
Reference doesn't exist: typography.bold.H1.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.bold.H1.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.bold.H1.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.bold.H1.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.bold.H1.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.bold.display.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.bold.display.value.fontWeight tries to reference fontWeights.regular, which is not defined
Reference doesn't exist: typography.bold.display.value.lineHeight tries to reference lineHeights.auto, which is not defined
Reference doesn't exist: typography.bold.display.value.fontSize tries to reference fontSize.display, which is not defined
Reference doesn't exist: typography.bold.display.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.bold.display.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.bold.display.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.bold.display.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.bold.display.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.italic.label.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.italic.label.value.fontWeight tries to reference fontWeights.italic, which is not defined
Reference doesn't exist: typography.italic.label.value.lineHeight tries to reference lineHeights.xxdense, which is not defined
Reference doesn't exist: typography.italic.label.value.fontSize tries to reference fontSize.label, which is not defined
Reference doesn't exist: typography.italic.label.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.italic.label.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.italic.label.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.italic.label.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.italic.label.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.italic.body.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.italic.body.value.fontWeight tries to reference fontWeights.italic, which is not defined
Reference doesn't exist: typography.italic.body.value.lineHeight tries to reference lineHeights.xdense, which is not defined
Reference doesn't exist: typography.italic.body.value.fontSize tries to reference fontSize.body, which is not defined
Reference doesn't exist: typography.italic.body.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.italic.body.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.italic.body.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.italic.body.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.italic.body.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.italic.largeBody.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.italic.largeBody.value.fontWeight tries to reference fontWeights.italic, which is not defined
Reference doesn't exist: typography.italic.largeBody.value.lineHeight tries to reference lineHeights.dense, which is not defined
Reference doesn't exist: typography.italic.largeBody.value.fontSize tries to reference fontSize.largeBody, which is not defined
Reference doesn't exist: typography.italic.largeBody.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.italic.largeBody.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.italic.largeBody.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.italic.largeBody.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.italic.largeBody.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.italic.H5.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.italic.H5.value.fontWeight tries to reference fontWeights.italic, which is not defined
Reference doesn't exist: typography.italic.H5.value.lineHeight tries to reference lineHeights.regular, which is not defined
Reference doesn't exist: typography.italic.H5.value.fontSize tries to reference fontSize.H5, which is not defined
Reference doesn't exist: typography.italic.H5.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.italic.H5.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.italic.H5.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.italic.H5.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.italic.H5.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.italic.H4.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.italic.H4.value.fontWeight tries to reference fontWeights.italic, which is not defined
Reference doesn't exist: typography.italic.H4.value.lineHeight tries to reference lineHeights.sparse, which is not defined
Reference doesn't exist: typography.italic.H4.value.fontSize tries to reference fontSize.H4, which is not defined
Reference doesn't exist: typography.italic.H4.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.italic.H4.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.italic.H4.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.italic.H4.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.italic.H4.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.italic.H3.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.italic.H3.value.fontWeight tries to reference fontWeights.italic, which is not defined
Reference doesn't exist: typography.italic.H3.value.lineHeight tries to reference lineHeights.xxsparse, which is not defined
Reference doesn't exist: typography.italic.H3.value.fontSize tries to reference fontSize.H3, which is not defined
Reference doesn't exist: typography.italic.H3.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.italic.H3.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.italic.H3.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.italic.H3.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.italic.H3.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.italic.H2.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.italic.H2.value.fontWeight tries to reference fontWeights.italic, which is not defined
Reference doesn't exist: typography.italic.H2.value.lineHeight tries to reference lineHeights.xxsparse, which is not defined
Reference doesn't exist: typography.italic.H2.value.fontSize tries to reference fontSize.H2, which is not defined
Reference doesn't exist: typography.italic.H2.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.italic.H2.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.italic.H2.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.italic.H2.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.italic.H2.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.italic.H1.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.italic.H1.value.fontWeight tries to reference fontWeights.italic, which is not defined
Reference doesn't exist: typography.italic.H1.value.lineHeight tries to reference lineHeights.xsparse, which is not defined
Reference doesn't exist: typography.italic.H1.value.fontSize tries to reference fontSize.H1, which is not defined
Reference doesn't exist: typography.italic.H1.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.italic.H1.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.italic.H1.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.italic.H1.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.italic.H1.value.textDecoration tries to reference textDecoration.none, which is not defined
Reference doesn't exist: typography.italic.display.value.fontFamily tries to reference fontFamilies.bc-sans, which is not defined
Reference doesn't exist: typography.italic.display.value.fontWeight tries to reference fontWeights.italic, which is not defined
Reference doesn't exist: typography.italic.display.value.lineHeight tries to reference lineHeights.auto, which is not defined
Reference doesn't exist: typography.italic.display.value.fontSize tries to reference fontSize.display, which is not defined
Reference doesn't exist: typography.italic.display.value.letterSpacing tries to reference letterSpacing.0, which is not defined
Reference doesn't exist: typography.italic.display.value.paragraphSpacing tries to reference paragraphSpacing.0, which is not defined
Reference doesn't exist: typography.italic.display.value.paragraphIndent tries to reference paragraphIndent.0, which is not defined
Reference doesn't exist: typography.italic.display.value.textCase tries to reference textCase.none, which is not defined
Reference doesn't exist: typography.italic.display.value.textDecoration tries to reference textDecoration.none, which is not defined


/Users/tykrys/code/design-tokens-test/node_modules/style-dictionary/lib/exportPlatform.js:125
    throw new Error('Problems were found when trying to resolve property references');
    ^

Error: Problems were found when trying to resolve property references
    at Object.exportPlatform (/Users/tykrys/code/design-tokens-test/node_modules/style-dictionary/lib/exportPlatform.js:125:11)
    at Object.cleanPlatform (/Users/tykrys/code/design-tokens-test/node_modules/style-dictionary/lib/cleanPlatform.js:46:21)
    at /Users/tykrys/code/design-tokens-test/node_modules/style-dictionary/lib/cleanAllPlatforms.js:27:10
    at Array.forEach (<anonymous>)
    at Object.cleanAllPlatforms (/Users/tykrys/code/design-tokens-test/node_modules/style-dictionary/lib/cleanAllPlatforms.js:26:39)
    at Object.<anonymous> (/Users/tykrys/code/design-tokens-test/build-output.js:55:4)
    at Module._compile (node:internal/modules/cjs/loader:1218:14)
    at Module._extensions..js (node:internal/modules/cjs/loader:1272:10)
    at Module.load (node:internal/modules/cjs/loader:1081:32)
    at Module._load (node:internal/modules/cjs/loader:922:12)

Node.js v18.13.0
```

## Style Dictionary Configurator links:

- [Non-working example](https://configurator.tokens.studio/#project=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), using the tokens exactly as they are coming out of Tokens Studio for Figma
- [Working example](https://configurator.tokens.studio/#project=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), where I have manually added `typography.` to each composite token
