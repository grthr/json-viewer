JSONViewer
=======
## information
* visualise JSON objects, root level may contains array or object
* special handling of _type property in objects

## use
* insert js & css files to your pages (see src/ folder)
* create new instance of JSONViewer object
* append instance container to the DOM using "getContainer()" method
* visualise json using "showJSON()" method, which accepts 3 arguments - json file, optional: visualise to max level (-1 unlimited, 0..n), optional: collapse all at level (-1 unlimited, 0..n)

## test
* see index.html for page

## credits
* create by Roman Makudera 2016 (c)
* modifications and fixes by Christian Grotheer 2022 (c)
* MIT licence, code is free to use
