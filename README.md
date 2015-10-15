# Auto-graded assignments within docker
Assignment submissions that are auto-graded in docker containers.

** DO NOT USE THIS ** It is for investigation only

## Testing docker
```
▶ cd tests/fixtures
▶ docker build -t autograde1 .
▶ docker run -t autograde1    
add() test passed!
subtract() test passed!
Final grade: 100
▶ echo $?
100
```

## Build environment
```
PHP 5.5 (/usr/bin/php55)
PHP 7.0 (/usr/bin/php70)
