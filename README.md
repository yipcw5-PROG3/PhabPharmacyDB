# PhabPharmacyDB

1. Install a Postgres database locally on your machine https://www.postgresql.org/download/
2. Open IntelliJ and select View->Tool Windows->Database
3. In the database window, click the plus button and add a data source of type PostgreSQL and use the
following values host:localhost, user:postgres, password:whatever you set when installing postgres,
Database:postgres.
4. Click Test Connection and it should be successful. Click OK and in the database window you should see your
database connection tree.
5. Click the QL icon at the top of the database window->New Console
6. Download the console.sql.html file from this repo and open it in a browser (eg Google Chrome). Copy the entire code to your clipboard.
7. On IntelliJ, paste the code in the console window and then click the go button (play button top left of console window):-
* All warnings/errors that mention "unsafe query" or "... already exists": execute or ignore as necessary.
