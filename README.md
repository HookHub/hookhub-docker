# hookhub-docker
Docker Compose repository to clone for easy start

## Use

### Local bootstrap

To use a local bootstrap configuration, copy `hookhub-bootstrap-local.sample.yml` to `hookhub.yml` and edit the `hookhub.yml` file to your needs.

### Remote/URL bootstrap
- Update the `docker-compose.yml` to use the [url based bootstrap module](https://github.com/hookhub/hookhub-bootstrap-local.git):
```
https://github.com/hookhub/hookhub-bootstrap-local.git
```
- Copy `hookhub-bootstrap-url.sample.yml` to `hookhub.yml` and configure as needed. The configuration is the YAML equivalent of the [request](https://www.npmjs.com/package/request) `options` object.

### Bundles
If you need to supply modules as files, use the `bundle` directory.

## More information

For more information, see the README at [Hookhub](https://github.com/HookHub/hookhub)