Very simple plugin.

Usage: 

    <script type="text/javascript" src="rfwadmin_files/jquery-1.10.2.min.js"></script>
    <script type="text/javascript" src="rfwadmin_files/jquery.escape.js"></script>
    <script type="text/javascript">alert($.escape('&<>"\''))</script>

I am not sure if the 
    $.escape = $.prototype.escape = function(...)
is the official jquery way of defining a method called without a context. Seems to work.