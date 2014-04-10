# ActionBar-PullToRefresh

This ActionBar-PullToRefresh is based on Chris Banes' [ActionBar-PullToRefresh](https://github.com/chrisbanes/ActionBar-PullToRefresh).

The original version of ActionBar-PullToRefresh is made for Gradle (and Android Studio). However, importing that project into Eclipse (Android Development Tools) is a pain-in-the-a**! This project can be imported directly into Eclipse and used right away.

---

## Changes to the original ActionBar-PullToRefresh

The original project allows customizing of the PullToRefresh view via an XML file (See the [Customisation](https://github.com/chrisbanes/ActionBar-PullToRefresh/wiki/Customisation) page for more information.). However, many times, you would want to change a really small attribute such as color of the progress bar, or color of the text. In that case, the XML file becomes an overkill (and too much work for lazy people like me!).

So I added a few more methods to the Options class


---

## Sample Apps (From Original Project)

There are two sample applications, the stock sample which uses the standard library and is therefore has a `minSdkVersion` of 14. There is also a sample which uses the ActionBarSherlock extra so has a `minSdkVersion` of 7.

### Stock Sample (From Original Project)
[![Get it on Google Play](http://www.android.com/images/brand/get_it_on_play_logo_small.png)](http://play.google.com/store/apps/details?id=uk.co.senab.actionbarpulltorefresh.samples.stock)

### ActionBarSherlock Sample (From Original Project)
[![Get it on Google Play](http://www.android.com/images/brand/get_it_on_play_logo_small.png)](http://play.google.com/store/apps/details?id=uk.co.senab.actionbarpulltorefresh.samples.actionbarsherlock)

## Video (From Original Project)

[![Sample Video](http://img.youtube.com/vi/YOYtPF-4RPg/0.jpg)](https://www.youtube.com/watch?v=YOYtPF-4RPg)

---

## Supported Views (As-is from original project)

ActionBar-PullToRefresh has in-built support for:

 * AbsListView derivatives (ListView & GridView).
 * ScrollView
 * WebView

If the View you want to use is not listed above, you can easily add support in your own code by providing a `ViewDelegate`. See the `ViewDelegate` section below for more info.

---

## Usage and Integration (As-is from Original project)
See the Quick Start guides for more information on how to achieve a simple integration:

* [Quick Start](https://github.com/chrisbanes/ActionBar-PullToRefresh/wiki/QuickStart-Stock) for API v14 and above.
* [Quick Start: ActionBarCompat](https://github.com/chrisbanes/ActionBar-PullToRefresh/wiki/QuickStart-ABC) when using ActionBarCompat (appcompat).
* [Quick Start: ActionBarSherlock](https://github.com/chrisbanes/ActionBar-PullToRefresh/wiki/QuickStart-ABS) when using ActionBarSherlock.

Then we are some advanced integration information:

* [ListFragment](https://github.com/chrisbanes/ActionBar-PullToRefresh/wiki/ListFragment) when integrating the library with a ListFragment.


## Customisation 
See the [Customisation](https://github.com/chrisbanes/ActionBar-PullToRefresh/wiki/Customisation) page for more information.

=======================
