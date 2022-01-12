Web requests handling
--
In this task we want to add some handleFunctions
* using of `"github.com/gorilla/mux"` is advised, but not mandatory
* func `Start(host string, port int)` is required to run tests. It should start web listener 
* All tests *must* pass  

Endpoints used by tests:

* `GET /name/{PARAM}`
* `GET /bad`
* `GET /data`
* `POST /data`