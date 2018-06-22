# phplint

Batch style syntax checking for PHP.  Tested and working on CentOS, FreeBSD.

Installation: place "lint" in your $PATH.  Name it something [_lintcmd_] that makes sense (I called it _lint_ on the CentOS system, which didn't have a 'lint' already installed; on FreeBSD, it's at _/usr/local/bin/phplint_ and called as _phplint_).

Usage:  _lintcmd_ $PWD

Output:

No syntax errors detected in /home/user/bar.php<br>
Errors parsing /home/user/baz.php<br>
No syntax errors detected in /home/user/foo
