# BotAuth Examples

Examples for the [BotAuth](https://github.com/MicrosoftDX/botauth) nodejs module which demonstrate how to authenticate a bot user, using the BotAuth authentication framework.  

## Examples
* [Facebook](facebook/)
* [Dropbox](dropbox/)
* [Rakuten](rakuten/)
* [Evernote](evernote/)
* [Azure AD v1](aadv1/) (coming soon)
* [Azure AD v2](aadv2/) (coming soon)
* [Visual Studio Online](vso/) (coming soon)

## About
All samples use environment variables to store sensitive configuration information like APP_IDs and APP_SECRETS.  Please see the documentation about each sample to know how to configure it so that it functions correctly.  Also, all samples expect to be hosted on a publically accessilbe HTTPS endpoint. If you're trying to run the sample on your local machine consider using something like [ngrok](https://ngrok.io) so you get SSL and a public endpoint instead of localhost.
