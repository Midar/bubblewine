bubblewine is a wrapper around wine that uses bubblewrap to properly sandbox
wine. By default, wine gives full access to the entire file system, while many
Windows binaries are potentially untrustworthy. The aim of bubblewine is to
properly sandbox wine so that one can execute Windows binaries on Linux with
ease of mind that it is unlikely the system gets compromized.
