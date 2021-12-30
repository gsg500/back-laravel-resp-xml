Laravel Response XML
Add the method "xml" integrating the laravel's response, converting eloquent return to XML.

Example
Route::get('/', function () {
    return response()->xml(User::all());
});
