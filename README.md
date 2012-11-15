# FakeCF

A simple sinatra app to attempt to mimick some Cloud Foundry data to fake out http://core.cloudfoundry.com/. Currently this provides the generic /info and /info/services data in json format. 

Currently this results in the core app throwing an error when trying to perform a deeper eval of the nonexistent environment.
