Components
==========

Package manager-friendly distributions of many popular [Components](http://github.com/components).

Note: Components is **NOT** a package manager.

What is it
----------
There are many packages managers... More than one for each language!
And for each one you need a mirror repository with built `*.js`.

Components is here to centralize this, having only one repository by project, supporting 
every package manager there is and keeping project repositories up-to-date.

**Keep it simple**: all Components repositories will be made available in the
official list of your package manager (naming may change based on said manager):
you don't have to do anything, just install our component like any other.

When we can extend the package manager, Components comes with some additionnal
features (the install directory for example).


Package Managers
----------------
Although package manager support varies from package to package, Components aims
to support as many package managers as possible. Some examples include:

* [npm](http://npmjs.org)
* [Bower](http://bower.io/)
* [Component](http://github.com/component/component)
* [Jam](http://jamjs.org)
* [volo](http://volojs.org)
* [Ender](http://ender.jit.su)
* [Composer](http://getcomposer.org), see [Components Installer for Composer](https://github.com/RobLoach/component-installer)
* [Package Manager Comparison](https://github.com/wilmoore/frontend-packagers)


Notes
-----
The Bower repositories try to have a standardized name of `components-*`.


Maintainers
-----------
If you are using grunt as part of the build process for your library, you can use this helper to release a new version of your library in the main repo, and the compiled version of your code to your component repository:

https://github.com/walmartlabs/grunt-release-component


Contributing
------------

If you see a Component that requires an update, or is missing support for a
certain package manager, feel free to open an issue or better, a pull request!
