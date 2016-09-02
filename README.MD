a Small Library For Generate an Unique Alphanumeric
____________________________________________________________

Inittial<br />
use Bonds23\Alphanumnique;

// Create new instance of generator class.<br />
$generator = new Alphanumnique;

// Set token length.<br />
$tokenLength = 32;

// Call method to generate random string.<br />
$token = $generator->generate($tokenLength);
