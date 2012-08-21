Known global before/after filters (nodeca.filters)
==================================================

**before**

- -9000 - `start_puncher` *nodeca.core/lib/puncher.js*
- -900 (http only) - `fix_vhost` *nodeca.core/lib/init/http.js*
- 50 - `inject_assets_info`  *nodeca.core/lib/inject_assets_info.js*

**after**

- 50 (http only) - `inject_menu` *nodeca.core/lib/inject_menu.js*
  *exclude: common.menus.permissions*
- 50 - `inject_users` *nodeca.users/lib/filters.js*
- 900 (http only) - `renderer` *nodeca.core/lib/init/http.js*
- 9000 - `finish_puncher` *nodeca.core/lib/puncher.js*