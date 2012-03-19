UI ThemeSwitcher for Rails
-------------

A Rails 3 wrapper for JQuery UI ThemeSwitcher by https://github.com/skamansam/jquery-ui-themeswitcher

Rails 3 Use/Install
-------------

In assets/javascripts/application.js

		//= require jquery
		//= require_tree .
		//= require jquery.ui.themeswitcher

In assets/stylesheets/application.css

		 *= require jquery.ui.themeswitcher
		*/


Custom Themes
-------------

In order to Add one or more custom themes, add an icon to represent the theme, a css file for the theme (use the Theme roller) and have any custom images also in the assets tree.
The configure themeswitcher to use these custom theme assets.

Please see https://github.com/skamansam/jquery-ui-themeswitcher/index.html and https://github.com/skamansam/jquery-ui-themeswitcher/css for an example.

Use the following configuration JSON model

		themes: {
			'My Theme':{
				icon: 'css/mytheme/mytheme.png',
				css:'css/mytheme/jquery-ui-1.8.9.custom.css'
			}
		},
		loadTheme:'base',
		imageLocation:"css/images/"

Contributing to ui_themeswitcher
--------------
 
* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
* Fork the project.
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

Copyright
---------------

Copyright (c) 2012 Kristian Mandrup. See LICENSE.txt for
further details.

