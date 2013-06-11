Full page wide, non-responsive content slider
=============================================

Files and Dependencies
----------------------
- slider.js
- app.js
- require.js

Using/Schema
------------

```
<body>
    <div class="page">
        <div class="slider" id="heroslider">
            <ul>
                <li class="slide"><div style="background-color:lightblue;">First page content</div></li>
                <li class="slide"><div style="background-color:yellow;">2nd page content</div></li>
                <li class="slide"><div style="background-color:red;">Last page content<button>Find out more</button></div></li>
            </ul>
        </div>
        <div class="slider" id="normalslider">
            <ul>
                <li class="slide"><div style="background-color:green;">First page content</div></li>
                <li class="slide"><div style="background-color:blue;">2nd page content</div></li>
                <li class="slide"><div style="background-color:purple;">Last page content<button>Find out more</button></div></li>
            </ul>
        </div>
    </div>


    <script type="text/javascript" data-main="app" src="require.js"></script>
</body>
```

Config/API
----------

Changelog
---------

**v1.0 (11 June 2013)**

- First release and documentation




