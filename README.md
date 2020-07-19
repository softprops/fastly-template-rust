# Fastly Compute@Edge template for Rust

A package template for Rust-based Fastly Compute@Edge projects equipped for continuous deployment with GitHub actions

## Usage

- Install the [Fastly CLI](https://github.com/fastly/cli#installation) to your `$PATH`

- Run 

```sh
fastly compute init \
  --from https://github.com/softprops/fastly-template-rust.git
```

- Create a new Fastly API Token [here](https://manage.fastly.com/account/personal/tokens)

- Securely save it it as `FASTLY_API_TOKEN` in your GitHub repository's secrets

- Git push to deploy