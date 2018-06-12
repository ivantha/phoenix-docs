## Installation instructions

### Prerequisites

You must have a URL to a valid instance of an ownCloud to test the Phoenix client.

### Setup

Clone the repository https://github.com/owncloud/phoenix to your machine.

Rename the config.json.sample within the cloned directory to config.json and add your ownCloud URL to the json file.

### How to build

Run `make`

### Run

Run a PHP test server `make run SERVER_HOST=0.0.0.0:8300`

You can test your client at, 0.0.0.0:8300

**If you are using a local ownCloud instance (i.e Docker), you'll have to disable CORS when visiting this address.**