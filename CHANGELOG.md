1.0.3 [WIP]

* 

1.0.2

* fixed return value of `get_language_details` on non-existent language
* fixed crash on `resize_image` with method `height`
* fixed root logger level (now DEBUG)
* removed useless `console=True` `getLogger` param
* completed tests (100% coverage)
* added `./test` script for quick local testing
* improved tox.ini
* added `create_favicon` to generate a squared favicon
* added `handle_user_provided_file` to handle user file/URL from param

1.0.1

* fixed fix_ogvjs_dist

1.0.0

* initial version providing
 * download: save_file, save_large_file
 * fix_ogvjs_dist
 * i18n: setlocale, get_language_details
 * imaging: get_colors, resize_image, is_hex_color
 * zim: ZimInfo, make_zim_file
