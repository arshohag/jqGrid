# free fork of jqGrid
[![npm version](https://img.shields.io/npm/v/free-jqgrid.svg?style=flat)](https://www.npmjs.com/package/free-jqgrid)![downloadstotal](https://img.shields.io/npm/dt/free-jqgrid.svg?style=flat-square)&nbsp;[![Bower](https://img.shields.io/bower/v/free-jqgrid.svg?style=flat-square)](http://bower.io/search/?q=free-jqgrid)&nbsp;[![NuGet](https://img.shields.io/nuget/v/free-jqgrid.svg?style=flat-square)](https://www.nuget.org/packages/free-jqGrid/)&nbsp;[![Maven Central](https://img.shields.io/maven-central/v/org.webjars.npm/free-jqgrid.svg?style=flat-square)](http://search.maven.org/#search%7Cga%7C1%7Cfree-jqgrid)<br>[![GitHub commits](https://img.shields.io/github/commits-since/free-jqgrid/jqgrid/v4.7.0.svg)](https://github.com/free-jqgrid/jqGrid/compare/v4.7.0...master)&nbsp;![time to close pull requests](https://img.shields.io/badge/pull%20requests%20closed%20in-about%203%20hours-brightgreen.svg?style=flat-square)![time to close issues](https://img.shields.io/badge/issues%20closed%20in-1%20day-yellowgreen.svg?style=flat-square)&nbsp;[![GitHub watchers](https://img.shields.io/github/watchers/free-jqgrid/jqGrid.svg)](https://github.com/free-jqgrid/jqGrid/watchers)[![GitHub forks](https://img.shields.io/github/forks/free-jqgrid/jqGrid.svg)](https://github.com/free-jqgrid/jqGrid/network)[![GitHub stars](https://img.shields.io/github/stars/free-jqgrid/jqGrid.svg)](https://github.com/free-jqgrid/jqGrid/stargazers)&nbsp;![devDependency status](https://david-dm.org/free-jqgrid/jqgrid/dev-status.svg)&nbsp;[![GitHub license](https://img.shields.io/badge/license-MIT%20or%20GNU%20GPLv2-blue.svg)](https://github.com/free-jqgrid/jqGrid/blob/master/LICENSE.md)
---
jqGrid is a popular jQuery Plugin for displaying and editing data in tabular form. It has some other more sophisticated features, like subgrids, TreeGrids, grouping and so on.

jqGrid was developed originally by [Tony Tomov](https://github.com/tonytomov) and it was available under MIT/GPL-licenses till the version 4.7.0 published Dec 8, 2014 (see [here](https://github.com/tonytomov/jqGrid/tree/v4.7.0)). Short time after that the license agreement was changed (see <a href="https://github.com/tonytomov/jqGrid/commit/1b2cb55c93ee8b279f15a3faf5a2f82a98da3b4c">here</a>) and new 4.7.1 version was <a href="https://github.com/tonytomov/jqGrid/tree/v4.7.1">published</a>.

The code from the GitHib repository is the fork of jqGrid 4.7.0 - the latest version available under MIT/GPL-licenses. It will be provided under MIT/GPL-licenses.

Below you can find short description of minor new features and the bug fixes implemented in free jqGrid 4.13.4 (compared with version 4.13.3). The version is developed by [Oleg Kiriljuk](https://github.com/OlegKi), alias [Oleg](http://stackoverflow.com/users/315935/oleg) on the stackoverflow and [OlegK](http://www.trirand.com/blog/?page_id=393) on trirand forum.

Read [Wiki](https://github.com/free-jqgrid/jqGrid/wiki) for more detailed information about the features of free-jqGrid. The preliminary version of the documentation can be found [here](http://free-jqgrid.github.io/).

Free jqGrid can be used *for free*. We still ask to contribute the development by donating via PayPal, if one have the possibility for it. One can donate by clicking on the following button [![PayPayl donate button](https://www.paypalobjects.com/webstatic/en_US/btn/btn_donate_pp_142x27.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=JGTCBLQM2BYHG "Donate once-off to free jqGrid project using PayPal") or by sending money via PayPal to oleg.kiriljuk@ok-soft-gmbh.com with the comment "free jqGrid". Bank transfer based on the invoice from OK soft GmbH is another option of donating. Just send the email with the information about the amount of donation and you will get the corresponding invoice with the full information about our bank account and our VAT number.

One can install the package with respect of [npm](https://www.npmjs.com/package/free-jqgrid) by using "npm install free-jqgrid", with respect of [bower](http://bower.io/search/?q=free-jqgrid) by using "bower install free-jqgrid" or from [NuGet](https://www.nuget.org/packages/free-jqGrid) by using "Install-Package free-jqGrid".

The package is published on [WebJars](http://www.webjars.org/) too and it's deployed to [Maven Central](http://search.maven.org/#search%7Cga%7C1%7Cfree-jqgrid).

Free jqGrid is is available from [jsDelivr CDN](http://www.jsdelivr.com/#!free-jqgrid) and [cdnjs](https://cdnjs.com/libraries/free-jqgrid). Thus one can use it directly from Internet by including for example the URLs like
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/free-jqgrid/4.13.4/css/ui.jqgrid.min.css">
<script src="https://cdn.jsdelivr.net/free-jqgrid/4.13.4/js/i18n/grid.locale-de.min.js"></script>
<script src="https://cdn.jsdelivr.net/free-jqgrid/4.13.4/js/jquery.jqgrid.min.js"></script>
```
or
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/free-jqgrid/4.13.4/css/ui.jqgrid.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/free-jqgrid/4.13.4/js/i18n/grid.locale-de.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/free-jqgrid/4.13.4/js/jquery.jqgrid.min.js"></script>
```
**The locale file is optional**. One can, but one don't need to include `grid.locale-en.min.js`, because the same information is already included in the `jquery.jqgrid.min.js` (or `jquery.jqgrid.src.js`).

If somebody want to test the *latest* version of free jqGrid, one can load it directly from GitHib using [RawGit](http://rawgit.com/) service:
```html
<link rel="stylesheet" href="https://rawgit.com/free-jqgrid/jqGrid/master/css/ui.jqgrid.css">
<script src="https://rawgit.com/free-jqgrid/jqGrid/master/js/i18n/grid.locale-de.js"></script>
<script src="https://rawgit.com/free-jqgrid/jqGrid/master/js/jquery.jqgrid.src.js"></script>
```
All other language files and plugins are available from CDN too. See [the wiki article](https://github.com/free-jqgrid/jqGrid/wiki/Access-free-jqGrid-from-different-CDNs) for more details about the usage of free jqGrid from CDNs and RawGit.

Remark: the above URLs will be available **after publishing** the release of the version of 4.13.4.

### Below one can see the full list of changes in the version 4.13.4 compared with 4.13.3:

* Add support on `IN` operation for local searching. The values should be comma separated.
* Bug fix initializing of `currentFilters` variable to {}. It's used in `filterToolbar`. The fix is important in case of usage `loadFilterDefaults: false` option of `filterToolbar`.
* Bug fix of idents in Searching Dialog in case of usage `overlay: 0` searching option.
* Add `mode` and `rowid` properties in the options of `selectFilled` callback and `jqGridSelectFilled` event.
* Bug fix: prevent id duplicates in `navButtonAdd` if id option is specified and there are more as one navigation bar (both `pager` and `toppager` are set).
* Bug fix of `selected` option in Chrome/Firefox in `filterToolbar` if `searchoptions.noFilterText` is used.
* Bug fix in `searchGrid` (Advanced Searching Dialog) to make `showQuery: true` option correctly working.
* Bug fix of `edittype: "select"` element selection by text or value (if text and values are different, but no `formatter: "select"` are used).
* Makes searching filter (created by `filterToolbar`) more compliant to WAI-ARIA 1.1 and WCAG 2.0 standards.
* Add the usage of `$.jgrid.defaults.fatalError` instead of `alert` over the whole code (the mothod `$.jgrid.defaults.fatalError` can be replaced to any custom implementation).
* Add `summary` parameter in `summaryFormat` callback used for data grouping. See [the issue](https://github.com/free-jqgrid/jqGrid/issues/232) for more detailes.
* Increases the value of the `size` attribute of the pager `<input>` based on the pager value. It improves the vivibility of the pager input if the total number of pages larger as 99.

Other readmes contain the list of the features and bug fixed implemented before:

* [README4.13.3.md](https://github.com/free-jqgrid/jqGrid/blob/master/README4.13.3.md) contains the readme of free jqGrid 4.13.2.
* [README4.13.2.md](https://github.com/free-jqgrid/jqGrid/blob/master/README4.13.2.md) contains the readme of free jqGrid 4.13.2.
* [README4.13.1.md](https://github.com/free-jqgrid/jqGrid/blob/master/README4.13.1.md) contains the readme of free jqGrid 4.13.1.
* [README4.13.0.md](https://github.com/free-jqgrid/jqGrid/blob/master/README4.13.0.md) contains the readme of free jqGrid 4.13.0.
* [README4.12.1.md](https://github.com/free-jqgrid/jqGrid/blob/master/README4.12.1.md) contains the readme of free jqGrid 4.12.1.
* [README4.12.0.md](https://github.com/free-jqgrid/jqGrid/blob/master/README4.12.0.md) contains the readme of free jqGrid 4.12.0.
* [README4.11.1.md](https://github.com/free-jqgrid/jqGrid/blob/master/README4.11.1.md) contains the readme of free jqGrid 4.11.1.
* [README4.11.0.md](https://github.com/free-jqgrid/jqGrid/blob/master/README4.11.0.md) contains the readme of free jqGrid 4.11.0.
* [README4.10.0.md](https://github.com/free-jqgrid/jqGrid/blob/master/README4.10.0.md) contains the readme of free jqGrid 4.10.0.
* [README492.md](https://github.com/free-jqgrid/jqGrid/blob/master/README492.md) contains the readme of free jqGrid 4.9.2.
* [README491.md](https://github.com/free-jqgrid/jqGrid/blob/master/README491.md) contains the readme of free jqGrid 4.9.1.
* [README49.md](https://github.com/free-jqgrid/jqGrid/blob/master/README49.md) contains the readme of free jqGrid 4.9.0.
* [README48.md](https://github.com/free-jqgrid/jqGrid/blob/master/README48.md) contains the readme of free jqGrid 4.8.0.

**Many thanks to all, who sent bug reports and suggestions to improve free jqGrid!**
