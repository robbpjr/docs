## Add API Authorization

To restrict access to the resources served by your API, check the incoming requests for valid authorization information. 
The authorization information is stored in the Access Token created for the user and needs to be sent in the `Authorization` header. To see if the token is valid, check it against the [JSON Web Key Set (JWKS)](/jwks) for your Auth0 account. To learn more about validating Access Tokens, read the [Verify Access Tokens tutorial](/api-auth/tutorials/verify-access-token).