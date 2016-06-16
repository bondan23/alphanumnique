a Small Library For Generate an Unique Alphanumeric
____________________________________________________________

Inittial<br />
use Utils\RandomStringGenerator;

// Create new instance of generator class.<br />
$generator = new RandomStringGenerator;

// Set token length.<br />
$tokenLength = 32;

// Call method to generate random string.<br />
$token = $generator->generate($tokenLength);