# solvahol/dns

DNS config for solvahol domains:

- solvahol.org

## Adding and changing things

Please:

- Before making changes, run [`script/bootstrap`] and [`script/setup`].
- After making changes, run [`script/test`] and address any issues.
- Refer to [**github/octodns**] documentation and source to learn about the `.yaml` files.

### Add or change records in an existing domain

1. Edit `<domain>.yaml`.

### Add a new domain

1. Update the top section of this README.
1. Create `<domain>.yaml`.
1. Add the new domain to `public.yaml`.

### Add a new DNS provider

1. Add credentials to `.env` and add GitHub secrets.
1. Update `public.yaml`.


[`script/bootstrap`]: <https://github.com/solvahol/dns/blob/main/script/bootstrap>
[`script/setup`]: <https://github.com/solvahol/dns/blob/main/script/setup>
[`script/test`]: <https://github.com/solvahol/dns/blob/main/script/test>
[**github/octodns**]: <https://github.com/github/octodns>
