# ntc-gpayment
ntc-gpayment is an example golang payment gateway  

## Quick start

### A. Create a ./.env file with your [API key](https://docs.adyen.com/development-resources/api-credentials#generate-your-api-key), [Client Key](https://docs.adyen.com/development-resources/client-side-authentication)
```shell
API_KEY="your_API_key_here"
MERCHANT_ACCOUNT="your_merchant_account_here"
CLIENT_KEY="your_client_key_here"
```

### B. Start the server:
```shell
## Install library dependencies
export GO111MODULE=on
go mod tidy

## Start server
go run -v .
```

### C. Visit [http://localhost:3000/](http://localhost:3000/) to select an integration type.

