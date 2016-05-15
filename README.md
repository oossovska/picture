# picture
малюнки
Саша@HomePC MINGW32 ~/Desktop/OCA (master)
$ git hist
git: 'hist' is not a git command. See 'git --help'.

Did you mean this?
        bisect

Саша@HomePC MINGW32 ~/Desktop/OCA (master)
$  git config --global user.name "Olga Ossovska"

Саша@HomePC MINGW32 ~/Desktop/OCA (master)
$ git config --global user.email "pavuchok@ua.fm"

Саша@HomePC MINGW32 ~/Desktop/OCA (master)
$  git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        deleted:    1.html
        renamed:    1.txt -> ola.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   Hello/hello.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .gitignore.txt
        oossovska/


Саша@HomePC MINGW32 ~/Desktop/OCA (master)
$ GIT LOG
fatal: cannot handle LOG.exe as a builtin

Саша@HomePC MINGW32 ~/Desktop/OCA (master)
$ git log
commit b37b76815aae6fd48744560e34b60f3f9de248f5
Author: Olga Ossovska <pavuchok@ua.fm>
Date:   Sat May 14 15:55:27 2016 +0300

    Hello/hello.txt

commit b151641f4c33fe3957236882d68981c43a62fe43
Author: Olga Ossovska <pavuchok@ua.fm>
Date:   Sat May 14 15:26:09 2016 +0300

    Hello/hello.txt

commit 2d8afaf5ed09b97ad5938be880e56bb3be384765
Author: Olga Ossovska <pavuchok@ua.fm>
Date:   Sat May 14 14:35:40 2016 +0300

    Unrelated change to 5

commit 22783d6037434f04e1fbe8850ba5819843297a09
Author: Olga Ossovska <pavuchok@ua.fm>
Date:   Sat May 14 13:38:25 2016 +0300

    Changes for 1 and 3

commit 2d881a4013cf6fbfa49d7f418bcd848cff059ee4
Author: Olga Ossovska <pavuchok@ua.fm>
Date:   Sat May 14 12:05:35 2016 +0300

    First commit
(END)
