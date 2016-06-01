This Jmeter script can be used to automate the process logging in users using SAML.

This has two steps. Step one is to login from IS instance 1 using SAML. Step two is to federate to another IS instance for basic authentication.
Please follow [1] to setup two identity server instances.

For the identity server in between (IS instance 1) Create an SP for travelocity. Issuer name should be travelocity.com.
By default script is using localhost. 

If you need to change any of the above two things you need to modify the saml request in the given script

[1] https://docs.wso2.com/display/IS500/Connecting+Two+Identity+Servers+with+SAML+SSO
