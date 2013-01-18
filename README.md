Clone the repository.
git submodule init should grab impress.js.
Open in web browser.

Notes:
* You'll want to change the app ID to your own app ID
* In your app settings, you should choose "Website with Facebook" and enter your localhost url (for local development) or website url (for deployment).

Local Development Example:
Website with Facebook -> enter in http://localhost:5000
Run `python -m SimpleHTTPServer 5000` in this directory. You should be able to load the index.html file by going to http://localhost:5000

Develop on your remote website Example:
Website with Facebook -> enter in http://yourwebsitename.com
Upload this project via FTP/SSH/whatever to yourwebsitename.com.
