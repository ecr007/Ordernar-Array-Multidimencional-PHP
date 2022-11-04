# Order multidimensional Array PHP

```php
array_multisort(array_column($records, 'year'), SORT_ASC,
                array_column($records, 'total'),      SORT_DESC,
                $records);
                
                ```
                
```php
usort($response['all'], function($a,$b) use($identifier){
    // DESC
    return onlyNumber($b[$identifier.'_curr_curr']) <=> onlyNumber($a[$identifier.'_curr_curr']);
    
    // ASC
    return onlyNumber($a[$identifier.'_curr_curr']) <=> onlyNumber($b[$identifier.'_curr_curr']);
});
```
