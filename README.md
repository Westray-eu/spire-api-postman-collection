# Spire API Postman Collection

A set of example HTTP requests for the Spire Sense APIs using the Postman API client. These include the following endpoints:

* **Vessels**
* **Messages**
* **Predict AI**

# Requirements

In order to utilize this repo you will need two things:

1. A [Spire API access token](https://spire.com/contact/developer-portal/).
1. [Postman](https://www.getpostman.com) for Mac, Windows, or Chrome.

# Setup

1. Clone or [download](https://github.com/kjbrazil/spire-api-postman-collection/archive/master.zip) this repo to your local machine.
1. Open Postman.
1. In the top left corner click "Import".
![Import](https://github.com/kjbrazil/spire-api-postman-collection/blob/master/images/import.png?raw=true)

1. Drag or find both the ``Spire_API.postman_collection.json`` & ``Spire.postman_environment.json`` files and click open.
![Drop Files](https://github.com/kjbrazil/spire-api-postman-collection/blob/master/images/drop_files.png?raw=true)
![Select Files](https://github.com/kjbrazil/spire-api-postman-collection/blob/master/images/select.png?raw=true)

1. Both the collection and the environment variables will be imported to Postman.
1. In the top right corner, click the gear icon and select "Manage Environments".
![Manage Environements](https://github.com/kjbrazil/spire-api-postman-collection/blob/master/images/environments.png?raw=true)

1. Click "Spire".
![Select Environment](https://github.com/kjbrazil/spire-api-postman-collection/blob/master/images/manage_environments.png?raw=true)

1. Locate the access token sent to you by the Spire Customer Experience team.
1. Navigate back to Postman and replace ``your-api-token`` with your actual credentials.
![Token](https://github.com/kjbrazil/spire-api-postman-collection/blob/master/images/token.png?raw=true)

1. Click "Update" and close the window.
1. Click the environment drop down again and select "Spire".
![Select Environment](https://github.com/kjbrazil/spire-api-postman-collection/blob/master/images/select_environment.png?raw=true)

1. You are now ready to start making API calls!
1. Try querying all Spire vessels by clicking the 01_Vessels folder > "List All Vessels" > Send.

![First Request](https://github.com/kjbrazil/spire-api-postman-collection/blob/master/images/first_request.png?raw=true)

# Support

If you encounter any issues please [email Spire Customer Experience](mailto:cx@spire.com). Please also feel free to improve upon the collection and submit pull requests. :-)