# Changelog

## v1.0.1 — 2026-10-21

> Draft: confirm this list against the previous public release before publishing.
> The v1.0.0 release tag is not available in the current checkout.

### Build and examples

- Move the UART, SPI, and USB Wi-Fi examples into the AT module repository and add a root Makefile for selecting and building an example.
- Reuse an existing SDK checkout or download the SDK and its submodules using the tag in BOUFFALO_SDK_VERSION (currently v2.3.36). Support an internal SDK mirror through SDK_REPOSITORY and an existing offline checkout through BL_SDK_BASE.
- Apply examples/sdk.patch when the selected SDK lacks external ATMODULE_PATH support, allowing standalone examples to use that SDK. SDKs already providing this support do not need the patch.
- Remove an overridden mbedTLS configuration setting and correct the SPI and USB example build instructions.

### Documentation

- Include English and Chinese AT command references with Sphinx HTML and optional PDF build instructions.
- Add docs/build_all.sh to build both English and Chinese HTML documentation in one command.

## v1.0.0 — 2026-10-19

> Draft: confirm this list against the previous public release before publishing.
> The v1.0.0 release tag is not available in the current checkout.

### Build and examples

- Move the UART, SPI, and USB Wi-Fi examples into the AT module repository and add a root Makefile for selecting and building an example.
- Reuse an existing SDK checkout or download the SDK and its submodules using the tag in BOUFFALO_SDK_VERSION (currently v2.3.36). Support an internal SDK mirror through SDK_REPOSITORY and an existing offline checkout through BL_SDK_BASE.
- Apply examples/sdk.patch when the selected SDK lacks external ATMODULE_PATH support, allowing standalone examples to use that SDK. SDKs already providing this support do not need the patch.
- Remove an overridden mbedTLS configuration setting and correct the SPI and USB example build instructions.

### Documentation

- Include English and Chinese AT command references with Sphinx HTML and optional PDF build instructions.
- Add docs/build_all.sh to build both English and Chinese HTML documentation in one command.
