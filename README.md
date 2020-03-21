# solvahol/dns

DNS config for solvahol domains:

- solvahol.org

## Adding and changing things

Please:

- Before making changes, run `script/update` and `script/setup`.
- After making changes, run `script/test` and address any issues.
- Changes will be deployed automatically when they're pushed to `master`.
- Refer to [**github/octodns**](https://github.com/github/octodns) documentation and source to learn about the `.yaml` files.

**_Add or change records in an existing domain:_**

1. Edit `<domain>.yaml`.

**_Add a new domain:_**

1. Update the top section of this README.
1. Create `<domain>.yaml`.
1. Add the new domain to `public.yaml`.

**_Add a new DNS provider:_**

1. Add credentials to `.env` and add GitHub secrets.
1. Update `public.yaml` and/or `private.yaml` as needed.

## To do

- Add self-hosted runner to deploy private.yaml. Update workflow and tests.
- Teach scripts about local and (GitHub Actions) workflow environments.
- Figure out how to run this action without Docker or NodeJS.
