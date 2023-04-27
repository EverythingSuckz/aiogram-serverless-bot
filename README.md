# Serverless Aiogram Bot
A template for running your aiogram bots on serverless functions.


## Hosting
### Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone)

> **Note**: After deployment, Goto the `/updateWebhooks?token=\<your bot token\>`  path of your deployed app url to setup webhooks.
> An example will be https://bot-name.vercel.app/updateWebhooks?token=your-bot-token

### Self Hosting

```bash
python -m bot
```

## Credits
- [aiogram](https://aiogram.dev/)
- [tg-serverless](https://github.com/illvart/tg-serverless)
- [fastapi-aiogram](https://github.com/malikovss/fastapi-aiogram)