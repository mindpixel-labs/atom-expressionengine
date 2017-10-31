# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## 1.1.0 - In Development
## Added
- Add list of keywords for variables and parameters
- Move category tag pair to categories.cson file
- Rename paginate snippet to pagination_links to avoid conflicts with channel entries parameter
- Add category snippets
- Breakout snippets to individual partials for better orginzation
- Rename files for better fuzzy search filtering within Atom when editing
- Add URL segment snippets
- Move variables and tags that can be used with or without braces to their own sections for more flexbility inside of conditional and module tags
- Add support for layout set tag
- Add full list of boolean comparison keywords
- Add negative look behind to ensure no characters are present with numerical values
- Add ability to match channel entries/module tags
- Separate conditional and module tags for more flexibility
- Remove old conditionals pattern
- Break out nested conditional patterns
- Correct boolean pattern heading comment
- Organize the grammar file
- Rename tag pattern to module-tags

## 1.0.0 - 2017-10-10
## Added
- Add title variable
- Add url_title variable
- Add page_url
- Add support for string concatenation operator
- Add changelog file

## Changed
- Remove ExpressionEngine from pagination boilerplate title

## Breaking Changes
- Remove lowercase versions that caused conflicts with parameters
- Rename channel entries tag snippet. Now uses **entries** instead of **exp** to trigger.


## 0.4.1 - 2017-10-06
### Added
- Organize patterns to match order of tag array
- Update readme file
- Added latest version of Atom tested
- Use flat-square badges

## 0.4.0 - 2017-10-06
### Added
- Add new double and single quote pattern using begin and ending matches
### Changed
- Fixed issue with variables not highlighting within quotes

## 0.3.0 - 2017-10-04
### Added
- Add quotes to capture groups for syntax highlighting
### Changed
- Update preview image in readme

## 0.2.4 - 2017-10-04
### Added
- Add missing issue and pull request templates

## 0.2.3 - 2017-10-04
### Added
- Add and encode twitter tweet badge text
### Changed
- Update readme status badge and twitter tweet text

## 0.2.2 - 2017-10-04
### Changed
- Move package description text above image preview in readme file

## 0.2.1 - 2017-10-04
### Added
- Add image preview to readme file

## 0.2.0 - 2017-10-04
### Added
- Add pagination tag and boilerplate snippet
- Add route snippet
- Add site_url, redirect and encode variable snippets
### Changed
- Regroup variables into global variables section

## 0.1.0 - 2017-10-04
### Added
- Initial release
