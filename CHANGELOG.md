## 4.2.2 - Minor Release
Release Date: 2016-10-31

### Whats New
* 2016-10-13 - TH - PR-XXX
 - added typings for listview and splitter.
 - SohoListViewComponent now uses Soho Control defaults for 'options'
* 2016-11-04 - TH - PR-XXX
 - Added module support for _@infor/sohoxi-angular_.
* 2016-11-07 - TH - PR-171 
 - added QUICKSTART.md for developers consuming the published NPM package
 - added DEVELOPER.md for SohoXi Angular Component developers
 - copy SohoXi CSS files to `src/assets` on build
 - added _lint_ and _code coverage_ to _unit-test_ npm script
 - automatically include SohoXi typings when consuming NPM package.
 
### Breaking Changes
* 2016-10-10 - TH - PR-118
    refactored SohoGridColumn -> SohoDataGridColumn
    refactored SohoSourceRequest -> SohoDataGridSourceRequest
    removed SohoDataGridConfiguration merged into SohoDataGridOptions
    refactored SohoResponseFunction -> SohoDataGridResponseFunction
    removed SohoDatagridSource (abstract class) for source functions