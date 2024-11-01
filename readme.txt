=== XML-RPC Update Check === 
Contributors: trogau
Tags: updates
Requires at least: 4.0
Tested up to: 4.2
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin provides XML-RPC methods for checking the update status of WordPress websites. 

== Description ==

You can query core, plugin, and themes individually, or check all at once. 

It defines four new methods:

- xmlrpcCoreUpdateCheck - checks core, returns true/false
- xmlrpcPluginUpdateCheck - checks plugins, returns true/false
- xmlrpcThemeUpdateCheck - checks themes, returns true/false
- xmlrpcUpdatesCheck - checks all of the above, returns an array of trues/falses.

The plugin was created primarily for WPUpCheck (http://trog.qgl.org/wpupcheck/), a simple
Windows application that remotely polls a WordPress site to see if updates are available.


== Installation ==

1. Install from WordPress plugins directory and activate. No further configuration required.

OR

1. Upload the extracted plugin to its own directory within the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

