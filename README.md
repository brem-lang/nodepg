npm install pg  to run the pgadmin

RangeError [ERR_SOCKET_BAD_PORT]: Port should be >= 0 and < 65536. Received NaN.
put this if you encounter this error
require('dotenv').config()

DeprecationWarning: Implicit disabling of certificate verification is deprecated and will be removed in pg 8. 
Specify `rejectUnauthorized: true` to require a valid CA or `rejectUnauthorized: false` to explicitly opt out of MITM protection.
put this if you encounter this error
ssl: {
     rejectUnauthorized:false
 },

