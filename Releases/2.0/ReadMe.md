# What's New
I have included both a Chat server and a Chat client with the new release. the chat server also logs chat messages into a text file locally to the install (log.txt) in UTC time.
The chat server does not have a config file but is started from the Incident Responder application machine. The chat client is standalone and allows for the configuration to 
be set to the incident responder chat server.

## Known Bug
Within the incident responder app, it is possible to start the chat client before starting the Chat server this will crash the app. I will be putting a check in 
the next release to look for this to avoid the crash. But otherwise the client and the Server work well together. 
The standalone client will crash if the server is not found at the configured location. that will also be fixed in the next release.
Because the logs for both the Incident responder and the server are written as things are happening, I have yet to see any data loss on either crash scenario. 
at least there is that. 

