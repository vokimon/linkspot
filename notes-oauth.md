# Notes on OAuth


http://www.slideshare.net/rohitsghatol/oauth-20-simplified

## Roles

- Resource owner: Person which resorces are to be shared among applications
- Client: Application that wants to access a given resource
- Resource server: Application that has the resources to be shared
- Auth server: Application that grants the identity of the applications

## Steps

- Client register on Auth Server
  - Id/Secret/Redirection
  
- Auth Request: Client -> Auth
  - The Client gets a secret from the Auth server
  - client_id / scope / redirect_uri / response_type ("code")
