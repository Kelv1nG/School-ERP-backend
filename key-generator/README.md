# Key Generator

This project creates a RSA key pair for signing JWTs in the PowerSync self hosted demo project.

# Installation

Install NPM dependencies

```bash
npm install
```

# Generating Keys

A key pair can be generated by executing the `start` script

```bash
npm run start
```

The YAML form of the public key will be printed to the console. Add this to the `client_auth->jwks->keys` section of `./config/powersync.yaml`.

The `DEMO_JWKS_PUBLIC_KEY` and `DEMO_JWKS_PUBLIC_KEY` values will be printed to the console.
Add these values to the `.env` file in the root of the repository.
