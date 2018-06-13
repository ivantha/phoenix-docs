## Installation instructions

### Prerequisites

You must have a URL to a valid instance of an ownCloud to test the Phoenix client.

### Setup

#### ownCloud

Follow the [official documentation](https://doc.owncloud.org/server/10.0/admin_manual/installation/system_requirements.html) to setup an instance of ownCloud.

#### Pheonix

Clone the repository https://github.com/owncloud/phoenix to your machine.

Rename the **config.json.sample** within the cloned directory to config.json and add your ownCloud URL to the json file.

### Build the project

Run `make`

### Run

Run a PHP test server `make run SERVER_HOST=0.0.0.0:8300`

You can test your client at, 0.0.0.0:8300

**If you are using a local ownCloud instance (i.e Docker), you'll have to disable CORS in order to test the Phoenix client.**

#### Safari

Disabling CORS is an in build functionality in Safari browser. Select,

`Develop -> Disable Cross-Origin Restrictions`

#### Chrome

You will have to use an extension similar to [Allow-Control-Allow-Origin: *](https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi?hl=en) in order to disable CORS.