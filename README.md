# SymfonyTestSite
This is a test project to help me learn and understand the Symfony 4 framework. 
None of the assets in this project are meant for release, thus no exact attribution will be given besides whatever is included in the used files.

## Running
To run the site, simply clone the repository to either a server or a local machine and then either use a production server such as apache, xamp, lamp, etc. to run the PHP application or use the built-in php server by running (from the project root) ``php bin/console server:start`` to run the internal server on ``https://localhost:8000``.

## Development
To create a new class, such as a controller, command, unit test, extension, etc., use the command ``php bin/console make:<class>``, run ``php bin/console make`` to display a list of makeable classes.
