# ZenCoding for mi #
=======

This script enables text editor "mi" to use Zen-Coding, powerful abbreviation features for HTML, CSS coding.

- Requirements: [SSSCoding.pm][SSSCPM], [mi](http://www.mimikaki.net/), Mac OS X 10.7 or higher

## Installation ##

1. Install **SSSCoding.pm**. Download from [SSSCoding.pm][SSSCPM] site. SSSCoding.pm is an Zen-Coding implementation in Perl.
2. Make sure your Perl Library Path. You can find it with a script on the terminal like `perl -e 'print $i++ . ":" . "$_\n" foreach @INC'`.
3. Copy or move SSSCoding.pm module into your Perl Library.
4. Install **zencoding.scpt**. Copy or move the workflow file into `~/Library/Application Support/mi/mode/Normal/tool` in case that you want to use it '**Normal**' mode. You can change it according to **your mode**.


## Thanks ##

**Otchy**, author of [SSSCoding.pm][SSSCPM]. His Perl Module implementation of Zen-Coding makes me create this workflow.

**makog**, [his blog](http://d.hatena.ne.jp/makog/20110706/1309969364) shows us approches to implement zencoding features for text editor "Jedit X" with AppleScript and SSSCoding.pm. This article inspired me to develop my automator services.

## Copyright ##

Copyright 2012 luminousspice. See LICENSE for details.

[SSSCPM]: http://www.otchy.net/20100225/zen-coding-for-perl/