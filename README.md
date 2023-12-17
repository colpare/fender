Colpare Fender
==============

Front-ENd Data Export Repository

Colpare's Fender (Front-ENd Data Export Repository) is a JavaScript-based plugin to export and arrange your JSON to Front-end

Documentation \[[#](#documentation)\]
-------------------------------------

The attribute name of the list or object must be the name of the key in its HTML code between \[\[\]\].

Example:

                {KEY:"Miranda-JS"}
                <h1>[[KEY]]</h1>
            

### Simple Array or Object integration

    <div id="box">
        <h1>[[name]]</h1>
        <h2>[[lastname]]</h2>
    </div>
    <script>
    var list = {"name": "Fresco", "lastname": "Sprite"};
    $("#box").fenderjs(list);
    </script>
    

### Simple Object list integration

    <div id="box">
        <h1>[[name]]</h1>
        <h2>[[lastname]]</h2>
    </div>
    <script>
    var list = [{"name": "Fresco", "lastname": "Sprite"},{"name": "Elder", "lastname": "Beat"}];
    $("#box").fenderjs(list);
    </script>
    

Examples \[#\]
==============

* * *

People
------

{{name}}

{{lastname}}

{{office}}

Company
-------

{{name}}

{{country}}
