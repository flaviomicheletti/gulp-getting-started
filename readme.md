![](gulp-bg-700x350.png)

# Gulp - getting-started 02

https://gulpjs.com/docs/en/getting-started/creating-tasks


Verificar as tasks...

    gulp --tasks

    [19:39:50] Tasks for ~/Documentos/codes-mygit/gulp-getting-started/gulpfile.js
    [19:39:50] └─┬ build
    [19:39:50]   └─┬ <series>
    [19:39:50]     ├── transpile
    [19:39:50]     └── livereload


Executar default

    gulp
    // Task never defined: default

Executar build

    gulp build

    [19:39:56] Using gulpfile ~/Documentos/codes-mygit/gulp-getting-started/gulpfile.js
    [19:39:56] Starting 'build'...
    [19:39:56] Starting 'transpile'...
    [19:39:56] Finished 'transpile' after 750 μs
    [19:39:56] Starting 'livereload'...
    [19:39:56] Finished 'livereload' after 397 μs
    [19:39:56] Finished 'build' after 3.63 ms

