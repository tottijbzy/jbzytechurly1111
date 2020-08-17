





[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/philhawksworth/linkylinky)

.

## Configuration

### 1. Environment variables
Netlify's [form handling](https://www.netlify.com/docs/form-handling/) and access the content via the provided [API](https://www.netlify.com/docs/api/#forms).

To do this we'll need to define the following Environment Variables:

-
- `API_AUTH` : Your netlify API authentication token. This will let your build script access the routes stored in your form programmatically. (Create one at https://app.netlify.com/account/applications)


### 2. Build hooks


