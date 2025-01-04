# awsssoprofiletool
Revamped version of AWS's [aws-sso-profile-tool](https://github.com/aws-samples/aws-sso-profile-tool)

## What are the changes?

The orginal script creates an sso profile to be a combination of the rolename and the account number (`read-only-123456789012`), this can be confusing with a multi account structure. 

This updates the profile name to be a combination of the role name and the account name, (`read-only-security`).

> [!NOTE]
> This will change all non-trailing whitespaces with a dash, `-`
