# go-meshbuf
Meshtastic golang protobuf

## How To update `Golang` Bindings:
- pull from the protobuf repo
- run the Makefile
- copy the files over into this repo at the TOP LEVEL so the package is properly setup
- ensure that all package names are `meshtastic` and no residual `generated` names are left
- bump and commit/tag/push !
- update `go.mod` for all users to the new version
