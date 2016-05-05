# TimezoneMapperPHP

Given a latitude and a longitude of a location, this program will return the timezone string.

This is the PHP version of the end product of: https://github.com/drtimcooper/LatLongToTimezone

It is released under the same license (MIT).

## Usage

```
<?php
include 'TimezoneMapper.php';
$london = ['lat' => 51.504380, 'lng' => -0.127727];
echo TimezoneMapper::latLngToTimezoneString($london['lat'], $london['lng']);
//outputs: Europe/London
```
