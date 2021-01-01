# vuedesktop

A [Sharp Desktop App](https://sharpscript.net/sharp-apps/) created using the [vue-desktop](https://github.com/NetCoreTemplates/vue-desktop) 
Project template whose published  `/dist` is deployed to this repo where its Desktop App can be launched with the [app dotnet tool](https://docs.servicestack.net/netcore-windows-desktop).

Where the `app://` [custom URL Scheme](https://sharpscript.net/sharp-apps/app-index) which can be launched via HTML Links:

### [app://mythz/vuedesktop](app://mythz/vuedesktop)

> Need to copy + paste URL in browser as GitHub markdown doesn't allow custom URL links

From the command-line:

    $ app open mythz/vuedesktop

Users can also download and run a local copy launched with a Windows Shortcut:

    $ app download mythz/vuedesktop && cd vuedesktop && app shortcut

This will download this repo and create a **Vue Desktop** Windows Shortcut you can use to launch this App:

![](https://raw.githubusercontent.com/ServiceStack/docs/master/docs/images/app/vue-desktop/vuedesktop-dist.png)

The **Vue Desktop** Shortcut can be moved elsewhere, e.g. to your Desktop for easy access to launch your App:

[![](https://raw.githubusercontent.com/ServiceStack/docs/master/docs/images/app/vue-desktop/vuedesktop-screenshot.png)](https://github.com/NetCoreTemplates/vue-desktop)