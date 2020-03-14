# @loopback/example-validation-app

An example application to demonstrate validation in LoopBack.

## Summary

This application shows how to add validation in a LoopBack application. It
exposes `/coffee-shops` endpoints to create/read/update/delete a CoffeeShop
instance with the in-memory storage.

### Key artifacts

- [CoffeeShop model](src/models/coffee-shop.model.ts)
  - Shows how to add validation using [AJV](https://www.npmjs.com/package/ajv)
- [ValidatePhoneNumInterceptor](src/interceptors/validate-phone-num.interceptor.ts)
  and [CoffeeShopController](src/controllers/coffee-shop.controller.ts)
  - Shows how to add reusable validation logic in interceptors

## Use

Start the app:

```sh
npm start
```

The application will start on port 3000. Open http://localhost:3000/explorer in
your browser. You can try to test the validation for the `/coffee-shops`
endpoints.

## Contributions

- [Guidelines](https://github.com/strongloop/loopback-next/blob/master/docs/CONTRIBUTING.md)
- [Join the team](https://github.com/strongloop/loopback-next/issues/110)

## Tests

Run `npm test` from the root folder.

## Contributors

See
[all contributors](https://github.com/strongloop/loopback-next/graphs/contributors).

## License

MIT

[![LoopBack](<https://github.com/strongloop/loopback-next/raw/master/docs/site/imgs/branding/Powered-by-LoopBack-Badge-(blue)-@2x.png>)](http://loopback.io/)
