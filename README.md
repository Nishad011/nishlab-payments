# NISHLAB payments site

Enrollment form for NISHLAB CREATIONS, published at https://payments.nishlabcreations.online

`index.html` holds placeholders such as `__PAY_SW_FULL__` instead of payment links.
The GitHub Actions workflow replaces them with repository secrets while building, then deploys to GitHub Pages.

## Secrets (Settings > Secrets and variables > Actions)
PAY_SW_FULL, PAY_SW_PART1, PAY_SW_BALANCE, PAY_AC_FULL, PAY_ACSW_FULL, PAY_SWAN_FULL

To change a link, update the secret and run the workflow again (Actions > Deploy payments site > Run workflow).
