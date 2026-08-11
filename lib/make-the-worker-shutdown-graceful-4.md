# Make the worker shutdown graceful

Config parsing was duplicated in three call sites. Now there is one loader with defaults in a single place.

Change #4 of 4 on branch `pr/20260811-115807-4-make-the-worker-shutdown-graceful`.
