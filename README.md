# codepathweek7assignment
# Project 7 - WordPress Pentesting

Time spent: **4** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) Vulnerability Name or ID  Unauthenticated Stored Cross-Site Scripting
  - [√] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2.2
    - Fixed in version: 4.2.3
  - [√] GIF Walkthrough: 
  <img src='http://i.imgur.com/qTVGyjn.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

  - [√] Steps to recreate: 
  - [√] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/class-wp-embed.php?rev=33359)
1. (Required) Vulnerability Name or ID  Accessibility Mode Cross-Site Request Forgery
  - [√] Summary: 
    - Vulnerability types: CSRF
    - Tested in version: 2.8-4.7
    - Fixed in version: 4.1.14
  - [√] GIF Walkthrough: 
    <img src='http://i.imgur.com/qTVGyjn.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

  - [√] Steps to recreate: 
  - [√] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/class-wp-theme.php?rev=36185)
1. (Required) Vulnerability Name or ID WP_Query SQL Injection
  - [√] Summary: 
    - Vulnerability types: SQL Injection
    - Tested in version: 3.5-4.7.1
    - Fixed in version: 4.1.15
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php) 

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [2017] [Indrajit Gurung]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
