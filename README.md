# Fastly Compute@Edge template for Rust

A package template for Rust-based Fastly Compute@Edge projects equipped for continuous deployment with GitHub actions

## Usage

- Install the [Fastly CLI](https://github.com/fastly/cli#installation) to your `$PATH`

- Run 

```sh
fastly compute init \
  --from https://github.com/softprops/fastly-template-rust.git
```

- Create a new Fastly API Token [here](https://manage.fastly.com/account/personal/tokens/new)

- Securely save it it as `FASTLY_API_TOKEN` in your GitHub repository's secrets

  > It's suggested you limit the scope of this token to the newly created service. Use the `service_id` in your applications `fastly.toml` file as a reference. 

- Git push to deploy