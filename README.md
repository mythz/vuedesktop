# vuedesktop

A [Sharp Desktop App](https://sharpscript.net/sharp-apps/) created using the [vue-desktop](https://github.com/NetCoreTemplates/vue-desktop) 
Project template whose published  `/dist` is deployed to this repo where its Desktop App can be launched with the [app dotnet tool](https://docs.servicestack.net/netcore-windows-desktop) where it can be launched by:

The `app://` URL Scheme which can be launched via HTML Links:

### [app://mythz/vuedesktop](app://mythz/vuedesktop)

> Need to copy + paste URL in browser as GitHub doesn't allow custom URL schemes.

From the command-line:

    $ app open mythz/vuedesktop

Users can also download and run a local copy launched with a Windows Shortcut:

    $ app download mythz/vuedesktop
    $ cd mythz/vuedesktop
    $ app shortcut

Then copy the **Vue Desktop** Shortcut to your Desktop where you can double-click it to launch your App:

[![](https://raw.githubusercontent.com/ServiceStack/docs/master/docs/images/app/vue-desktop/vuedesktop-screenshot.png)](https://github.com/NetCoreTemplates/vue-desktop)