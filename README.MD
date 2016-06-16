a Small Library For Generate an Unique Alphanumeric
____________________________________________________________

Inittial
use Utils\RandomStringGenerator;

// Create new instance of generator class.
$generator = new RandomStringGenerator;

// Set token length.
$tokenLength = 32;

// Call method to generate random string.
$token = $generator->generate($tokenLength);