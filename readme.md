Verifies translations integrity given a path to JSON translation files and an array of supported languages (JSON file names that should be supported)

## Example

``` js
  var path = require('path');
  var DIR = path.resolve(__dirname, 'pathToTranslations');
  var verifyTranslations = require('verify-translations');

  var hasTranslationsIntegrity = verifyTranslations(DIR, ['de', 'en']);
```


## API

``` js
  var verifyTranslations = require('verify-translations');
```
### verifyTranslations(pathToTranslations, [supportedTranslations])

Verifies translations integrity given a path to JSON translation files and an array of supported languages (JSON file names that should be supported)
Returns Boolean by comparing JSON object key structure.



