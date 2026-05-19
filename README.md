Run

* ssh -p PORT_FROM_WORKFLOW_OUTPUT -L8730:localhost:8730 runner@rendezvous.namespace.so
* rsync -a --progress --exclude=build --exclude=.pixi --exclude=.git . rsync://localhost:8730/debugger/debugger/work
