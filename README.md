### Amazon KMS Client

For encrypting and decrypting using a specific key from amazons kms

### Install



### Instructions

    kms-client encrypt <value> <region> <AWS key UUID> -ak <AWS access key> -sk <AWS secret key>
    kms-client decrypt <value> <region> -ak <AWS access key> -sk <AWS secret key>
    
The aws access key and secret key is not needed if stored as environment variables, system properties or 
the aws credentials file in the user's home. One way to do this is by executing [mai](http://docs.stups.io/en/latest/components/mai.html) 
prior to the kms-client.

The values input and returned are in base 64 encoding

### Options 

-c Copy to clipboard