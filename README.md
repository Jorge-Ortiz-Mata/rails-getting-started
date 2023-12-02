# Rails Getting Started

This is a template can be used for new applications. It includes the user authentication with Sendgrid to confirm email accounts.
What you need to start developing locally is:

- SENDGRID_EMAIL_VALID='user@email.com'
- SENDGRID_API_KEY='SG.XXX'

And generate a new master key each time.

- Delete the credentialas.yml.enc file
- Generate a new master key with the command: `EDITOR="code --wait" bin/rails credentials:edit`

And that's it.

## Authors

- Jorge Ortiz
- ortiz.mata.jorge@gmail.com
- yorch-devs.com
- San Luis Potosí, S.L.P. México
