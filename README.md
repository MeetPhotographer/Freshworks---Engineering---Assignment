# Freshworks---Engineering---Assignment

INSTRUCTIONS:

In this "Freshworks - Engineering - Assignment1.ipynb" file, File Concept is used as follows:
1. File "data.py" is created in the parent directory in which this file is present.
2. First of all, file "data.py" is created for create function with specified values.
3. Then it reads data from the file.
4. At last it leaves the file with empty dictionary and deletes all the performed functionality.

This code satisfies all the mentioned functional requirements for create, read, delete operations as:
1. with key-value pair as string-capped at 32 chars.
2. with value as JSON Object capped at 16KB.
3. all possible error messages.
4. with "time-to-live" properpty(optional) with all mentioned conditions.

And non-functional requirements as follows:
1. Satisfies file size of <= 1GB
2. Only one client is allowed at a time
3. It is a thread-safe i.e. it allows to access the datastore using multiple threads.
4. Uses less memory.

Requirements:
1. Python should be of version 3.x or above.
2. Otherwise use "import thread" for importing thread library for python2.0 version.
