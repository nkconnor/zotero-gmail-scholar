# zotero-gmail-scholar
Add journal articles discovered through Google Scholar's "Keyword Alert Service" directly to Zotero. Google Scholar lets you [observe keywords](https://scholar.google.com/scholar_alerts?view_op=list_alerts) and be notified when journal articles are discovered that contain some of the words.
Unfortunately, Scholar only let's you push those notifications to your email address. Adding them to Zotero is tedious - it can, should and therefore will be automated thanks to the magic of APIs!

# Install
## On the Server
    vagrant up && vagrant ssh       # set up vagrant box and log in
    cd /app/server && npm install   # install npm dependencies
    bin/www                         # start the app
## Account Info
1. a
2. b
3. ??
4. profit!!!!

## How does it work?
This software changes nothing about the fundamental workings of notifications in Google Scholar; but: the software automatically extracts the relevant information (metadata) regarding the recommendations sent by Goole Scholar. Those are then written to the Zotero Sync Server!
