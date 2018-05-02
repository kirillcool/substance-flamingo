## Substance plugin for Flamingo component suite

<img src="https://raw.githubusercontent.com/kirill-grouchnikov/substance-flamingo/master/www/images/ribbon-blue.png" width="720" height="408" border=0>

This project provides a [Substance](https://github.com/kirill-grouchnikov/substance) plugin for the [Flamingo component suite](https://github.com/kirill-grouchnikov/flamingo).

To use this plugin add the matching `substance-flamingo-X.Y.Z.jar` to the classpath of your application and add this call *before* creating the `JRibbonFrame` in your initialization sequence:

`SubstanceCortex.GlobalScope.registerComponentPlugin(new SubstanceFlamingoPlugin());`

Substance will then install the matching UI delegates on the Flamingo components used in the application.
