==========================================================
    jQuery gallery plugin (a la google plus gallery)
==========================================================

Gallery that resizes the images to fit the container width and show zoomed in images on hover.


Usage
=====

::

    $(container_selector).gpGallery(item_selector)

Where ``container_selector`` and ``item_selector`` are string containing jquery expressions for
selecting elements. You want to have the ``container_selector`` matching a single element.

Example::

    <div class="pictures">
        <img src="untitled-3-2.jpg" width="267" height="400"/>
        <img src="untitled-3-16.jpg" width="400" height="267"/>
        <img src="untitled-3-5.jpg" width="400" height="267"/>
        ...
    </div>

    <script>
        $('.pictures').gpGallery('img');
    </script>

*Note:*

    Items should have sizes. Either specify the sizes on the images or whatnot or run the gpGallery
    code *after* the document is rendered (and sizes are available).

Demo
====

http://jquery-gp-gallery.ionelmc.ro/demo/

