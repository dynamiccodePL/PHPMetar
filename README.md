# PHPMetar
PHP METAR decoder is a simple class to decode METAR codes.

# Example use

$metar = new PHPMetar();

// Single decoding

$metar->decode('EPWA 162200Z 20005KT CAVOK 08/02 Q1019 NOSIG');

// Multiple decode

$metar->decode(['EPWA 1622...', 'EPWA 1622...', 'EPWA 1622...']);

// Output: 'text', 'list', 'table' 

$metar->output('table');


# License
This software is distributed under the GPL license.
