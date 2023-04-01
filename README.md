# azure-test-app
test auth with azure application.


create .env file like in example: 

CLOUD_INSTANCE="https://login.microsoftonline.com/" # cloud instance string should end with a trailing slash
TENANT_ID=""
CLIENT_ID=""
CLIENT_SECRET=""

REDIRECT_URI="http://localhost:3000/auth/redirect"
POST_LOGOUT_REDIRECT_URI="http://localhost:3000"

GRAPH_API_ENDPOINT="https://graph.microsoft.com/" # graph api endpoint string should end with a trailing slash

EXPRESS_SESSION_SECRET="tsePnq6wgX"
