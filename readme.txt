=== Local Gravatars ===
Contributors: aristath
Requires at least: 5.5
Tested up to: 5.5
Requires PHP: 5.6
Stable tag: 1.1.0
License: MIT
License URI: https://opensource.org/licenses/MIT

Locally host gravatars for the privacy-concious.

== Description ==

Allow your users to use gravatars, but without sacrificing privacy.

The plugin will get your users gravatars and host them locally on your website.
Your visitors will get the gravatars directly from your website instead of the gravatar CDN, therefore increasing privacy and performance.

To avoid cluttering the filesystem and to allow refreshing gravatars, the files get flushed on a weekly basis (interval can be modified using a filter).
To avoid performance issues server-side, the download process for gravatars is limited to a maximum of 5 seconds (value can be modified using a filter).

The code is simple, easy to read, well-documented and includes filters you can use to modify the behavior of the plugin:

* Changing the folder where gravatars get downloaded.
* Change the URL of downloaded gravatars.
* Change the cleanup frequency.
* Change the maximum process time to avoid performance issues.
* Change the fallback image to use (defaults to blank) - also allows using the remote URL (not recommended as it will defeat the purpose of this privacy enhancement).