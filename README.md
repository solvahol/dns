# solvahol/dns

DNS config for solvahol domains:

- solvahol.org

## Adding and changing things

Please:

- Before making changes, run [`script/bootstrap`] and address any issues.
- After making changes, run [`script/test`] and address any issues.
- Refer to [**octodns/octodns**] documentation and source to learn about the `.yaml` files.

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
[`script/test`]: <https://github.com/solvahol/dns/blob/main/script/test>
[**octodns/octodns**]: <https://github.com/octodns/octodns>
