What is this package?
=====================

This package contains a basic renderer to render in HTML a menu (using &lt;ul&gt; and &lt;li&gt; tags).
The renderer is making extensive use of objects declared in the (mouf\html.widgets.menu)[https://github.com/thecodingmachine/html.widgets.menu] package).

Mouf package
------------

This package is part of Mouf (http://mouf-php.com), an effort to ensure good developing practices by providing a graphical dependency injection framework.
Using Mouf's user interface, you can create your menu graphically, by creating instances of Menu and MenuItem.

In practice
-----------

A menu is defined using the Menu class.
The Menu class can contain many MenuItem. Each menuitem can contain many MenuItem.
You pass a Menu instance to the BasicMenuRenderer::toHtml and it will render the menu. 