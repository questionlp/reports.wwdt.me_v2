# Wait Wait Don't Tell Me! Reports

## Overview

Flask-based web application that serves up a collection of reports based on collected statistics and details for the NPR weekly quiz show [Wait Wait... Don't Tell Me!](http://waitwait.npr.org).

## Requirements

- Python 3.10 or newer
- MySQL Server 8.0 or newer (or another MySQL Server distribution based on MySQL Server 8.0 or newer) or MariaDB Server 11.4.2 or newer *(Experimental)*

**Note:** Experimental support for MariaDB Server is only available starting with version 2.10.0 of the application. Older versions of MariaDB Server are not supported.

Also, due to potential incompatibilities with the divergence of MySQL and MariaDB, including the Python Connector libraries, support for MariaDB may not be feasible in the long term.

## Installation

Refer to [INSTALLING.md](./INSTALLING.md) for information on how to set up an instance of this web application that can be served through NGINX and Gunicorn.

## Changes

For changelogs, refer to [CHANGELOG.md](./CHANGELOG.md).

## Contributing

If you would like contribute to this project, please make sure to review both the [Code of Conduct](./CODE_OF_CONDUCT.md) and the [Contributing](./CONTRIBUTING.md) documents in this repository.

## License

This web application is licensed under the terms of the [Apache License 2.0](./LICENSE).

Original version of the Apache License 2.0 can also be found at: <http://www.apache.org/licenses/LICENSE-2.0>.
