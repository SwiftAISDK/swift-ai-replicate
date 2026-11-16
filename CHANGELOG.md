# Changelog

## 1.2.0

- Video no longer sends the `prefer` header and supports async start/status with webhooks; `num_outputs` is always sent; `maxImagesPerCall` is 8 for Flux-2 and 1 otherwise.
  Compatibility: Source-compatible; changes are additive. Request bodies, results, warnings and errors change to match the reviewed upstream package.
