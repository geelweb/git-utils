# Git pre-commit hook

Git pre-commit hook to check file syntax and coding standard respects on

 - PHP files (*.php) with `php -l` and `phpcs --standard=ZEND`
 - Javascript files (*.js) with `jslint`
 - Perl files (*.pl, *.pm) with `perl -c`
 - Python files (*.py) with `pylint` or `django-lint`
 - Bash files (*.sh) with `bash -n` and `checkbashisms`

