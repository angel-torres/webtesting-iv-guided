# server testing

## components of an api

function name(args) => return something;

- routes/endpoints: url(data) => return response;
- business logic (validation/data conversion/operations).
- data access: talk to the persistent data store.


cross-env = npmpackage used to abstract away OS differences setting env vars

set the test environment to run on 'node' instead of a browser
