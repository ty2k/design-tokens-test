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
