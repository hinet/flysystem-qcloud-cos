# flysystem-qcloud-cos
腾讯云COS文件存储

```php

$config = [
    'bucket' => 'testbucket',
];

$storage = new Filesystem(new QcloudAdapter($config));

$storage->getMetadata('xxx.png');

```
