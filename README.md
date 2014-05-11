angular-simplemediapicker 
=================
created by J&W Templates

<br>
Angular directive for <b>Wordpress</b> native simplemediapicker.

* Compatible with wordpress 3.5+

Documentation
=================

Add to your form this directive:

``` <div simplemediapicker name="NAME" ng-model="media"  ng-init="media = JSON.parse(\'' . addslashes(str_replace('"', '\'', $meta)) . '\');" ></div> ```


In WP < 3.9 you have to linked also mce-view.js (wordpress library).  

``` wp_enqueue_script('mce-view'); ```

In post (custom post) editor is linked automatically by WP.

mod ('list')
----
* list - lists names of the files
* img - shows pictures

multiple (true)
----
If true, more files can be chosen


