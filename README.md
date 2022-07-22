# Send email using Node.js / Twilio SendGrid Web API 

1. Create [Sender identity](https://app.sendgrid.com/settings/sender_auth/senders/new) or [Authenticate your domain](https://app.sendgrid.com/settings/sender_auth/domain/create)
2. Follow the [Email WebAPI Node.js guide](https://app.sendgrid.com/guide/integrate/langs/nodejs)
    - Tldr: Get the API Key and add it to `sendgrid.env` as below 
    ```
    echo "export SENDGRID_API_KEY='YOUR_API_KEY'" > sendgrid.env
    echo "sendgrid.env" >> .gitignore
    source ./sendgrid.env
    ```

# Run 
```node
node app.js
```
