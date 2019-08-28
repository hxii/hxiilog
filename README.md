# hxiilog
very simple, constantly evolving logger class for stuff and things

## Usage
```
include ('hxii-log.php');

$log = new Hxii_Logger('file.log', 'warn');

$log->info('This is an info line!');
$log->warn('This is a warn line!');
$log->debug('This is a debug line!');
```
