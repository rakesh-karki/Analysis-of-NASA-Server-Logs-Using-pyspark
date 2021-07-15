# Analysis of NASA Server Logs Using pyspark
In this project, we will be conducting various data analysis with a file containing one month of server log data collected from NASA.gov in August 1995.  
Each line in this file contains 6 pieces of information, separated by spaces. These pieces of information are, in order:
1. The IP address or DNS hostname of the server making the request.
2. The date and time of the request.
3. The request type. This has four possible values: GET, POST, and HEAD.
4. The location of the resource being requested.
5. The HTTP status code the server sent back to the client.
6. The number of bytes transferred to the client. This is set as a hyphen character '-' in some records.
