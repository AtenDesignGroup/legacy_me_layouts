# Legacy Mercury Editor Layouts

In Mercury Editor 2.2.x releases, layout and style option plugins have been
removed as part of an effort to make it possible to uninstall ME without
consequences (other than loosing the authoring enhancements directly provided
by the module).

The legacy_me_layouts module provides support for the legacy layouts removed
from Mercury Editor.

## To use this module:

* Add the repo to composer: `composer config repositories.legacy_me_layouts vcs https://github.com/AtenDesignGroup/legacy_me_layouts.git`
* Install the module with composer: `composer require atendesigngroup/legacy_me_layouts`
* Enable the module: `drush en legacy_me_layouts`
* Upgrade Mercury Editor with composer: `composer require drupal/mercury_editor:^2.1`
* Clear the cache: `drush cr`
* Replace any references in your themes/modules from `mercury_editor/layouts` to `legacy_me_layouts/layout`.
* Test and verify all layouts are rendering correctly.f

