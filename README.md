# ampath-remote-sync-server
Server for ampath incremental remote sync
To use rename the config.json.example to config.json and set your own configurations.

Create a database called remote_sync and import remote_sync.sql

Run ```node node mysql-backup.js ``` to generate the sync dumps and ```node server.js``` to run the meta data endpoint.
