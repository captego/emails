### TL;DR Info

- Emails are written using MJML - https://mjml.io/
- Recommended editor for macOS - https://mjmlio.github.io/mjml-app/
- Images are uploaded using SendGrid - https://mc.sendgrid.com/design-library/your-images
- Email HTML are uploaded to SendGrid - https://mc.sendgrid.com/dynamic-templates

### How to edit

Using this app: https://mjmlio.github.io/mjml-app/ it's possible to edit and preview the emails, then using the "Copy HTML" feature, it can be pasted directly into SendGrid in the "Dynamic Templates" section: https://mc.sendgrid.com/dynamic-templates

> There are VSCode plugins but for me they got stuck on "MJML needs to be rebuilt for your current platform", so I went with the separate app approach instead

SendGrid supports Handlebars syntax, it is used for all variables and also localization: https://docs.sendgrid.com/for-developers/sending-email/using-handlebars

### Assets

Upload images on SendGrid to be able to access them in the templates: https://mc.sendgrid.com/design-library/your-images

