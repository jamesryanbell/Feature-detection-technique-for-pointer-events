Modernizr plugin feature detection for css property "pointer-events"
====================================================================

How to use
----------

    <script src="modernizr-pointerevents.min.js"></script>
    <script>
        if(Modernizr.pointerevents){
            alert('pointer events are supported :)');
        }
        else{
            alert('pointer events are NOT supported!');
        }
    </script>

Example / testing
-----------------

[on this page][] you can see the Modernizr plugin in action
[on this page]: http://ausi.github.com/Feature-detection-technique-for-pointer-events/

Currently tested browsers (extensions are welcome!)
---------------------------------------------------

### pointer-events supported
- Firefox 6
- Safari 5
- Safari on iOS 4.3
- Chrome 14

### pointer-events not supported
- InternetExplorer 6, 7, 8, 9
- Opera 10
