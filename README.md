Open Document Merger
===

This small module allows you to merge libre office document with ODS extension.

This is full xml processing and especially useful if you don't want to use any third party tool (this is in pure javascript).

Here is a small example:

~~~javascript
    var merger = require('od-merger');

    // We can merge a set of files into one file
    var files = [ 'file1.ods', 'file2.ods', 'file3.ods' ];
    merger.merge(files, 'merged.ods');

    // We can merge a directory into one file
    merger.merge('mydir/', 'merged.ods');
~~~

