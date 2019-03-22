# go-mime
Get the mime type / content type of a file from its extension without external dependencies

# Why
We wanted a simple mime library that gives a consistent result on each environment. The golang mime package (https://golang.org/pkg/mime/) loads the list of mime types using the OS, meaning you get a different list depending on OS and OS version. On Windows this depends on the programs installed and whether the user running the process has access to the registry. 

# Mime Source
The mime list are sourced from here: https://github.com/micnic/mime.json
