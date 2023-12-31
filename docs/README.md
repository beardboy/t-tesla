# Introduction

This is an unofficial documentation of the Tesla Solar Local and Tesla Owner REST API.

## Contributing

We welcome your contributions! Please feel free to submit [pull requests](https://github.com/beardboy/t-tesla/pulls) with any changes or additions you'd like to make. Your assistance is highly appreciated!

## Getting Started - Local API

To begin, set up your Gateway on your local WiFi network by following Tesla's instructions available at:

- [Connecting to Tesla Gateway and Powerwall](https://www.tesla.com/support/energy/powerwall/own/connecting-network)

After successfully connecting the Gateway to your local network, you can retrieve its local IP Address by checking the list of connected devices on your WiFi router.

Once you have obtained the Gateway's local IP Address, try accessing it from your computer's web browser. You should be able to log in just as you did during Tesla's documentation.

### Testing

Use the local IP Address and [login](local-api/login.md) endpoint to get a token that will be used as the Bearer Token for all future requests.

#### GET `https://<local-ip-address>/api/login/Basic`

## Getting Started - Tesla Owner API

Get a Tesla Owner Access Token ([authentication](owner-api/authentication.md)) and begin making requests.

## Coming Soon

More coming soon.
- Tesla Solar CLI
- Additional documentation

## Thanks

We are immensely grateful to the dedicated individuals in the community whose work has been instrumental in our journey. Their contributions have proven invaluable, and we extend our deepest appreciation to:

- [https://tesla-api.timdorr.com/](https://tesla-api.timdorr.com/)
- [https://github.com/vloschiavo/powerwall2](https://github.com/vloschiavo/powerwall2)
