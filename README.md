# A Laravel Nepali Date.

A laravel date package which convert AD to BS and viceversa.

#Installation

You can install the package via composer:

```bash
composer require laratech/bsdate
```

## Usage

```php
Bsdate::eng_to_nep(2016,12,31); //For converting AD TO BS
Bsdate::nep_to_eng(2073,09,16); //For converting BS TO AD
// output 
Array
(
    [year] => २०७३
    [month] => ९
    [date] => १६
    [day] => शनिबार
    [nmonth] => पुष
    [num_day] => ७
)
```


