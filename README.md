# vue-cli-plugin-cypress-django

**NOTE: This package is very much experimental**

This is a fork/copy of the [vue-cli-plugin-e2e-cypress](https://github.com/vuejs/vue-cli/tree/2669008ea271b0614b7dcbc13572a9dab6759fee/packages/%40vue/cli-plugin-e2e-cypress).

What it does:

- Starts django server with `DJANGO_ENV=TestE2E`. (Currently it assumes that there's `../bin/manage.py` from the project's root)
- Starts a vue-cli dev server
- Runs tests with cypress
- Stops the django server
- Stops the vue-cli dev server
