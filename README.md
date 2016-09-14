# Yii2 Cyrillic Slug Behavior

## Install
```bash
composer require --prefer-dist nsept/yii2-cyrillic-slug-behavior "*"
```

### Usage

```php
public function behaviors()
{
    return [
        [
            'class' => \nsept\behaviors\CyrillicSlugBehavior::className()
            //'attribute' => 'title'
            //'slugAttribute' => 'slug',
        ]
    ];
}
```
