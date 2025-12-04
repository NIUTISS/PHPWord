# PHPWord

[Source](https://github.com/NIUTISS/PHPWord)

A pure PHP library for reading and writing word processing documents. Fork adds support for image alt attribute.

## Installation using composer

Update composer.json to include the following:

```json
{
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/niutiss/phpword"
    }
  ],
  "require": {
    "phpoffice/phpword": "dev-main"
  }
}
```

Run composer install

## Usage Example

```php
// Add an image with alt text
$section->addImage(storage_path('img/niu_logo_alt.jpg'), [
    'width' => 160,
    'height' => 40,
    'alignment' => Jc::START,
    'alt' => 'Northern Illinois University logo'
]);
```

## Notes

Please contact us at [ulibsysoff@niu.edu](mailto:ulibsysoff@niu.edu) if you have any questions.
