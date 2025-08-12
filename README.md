# Workflows

Reusable GitHub workflows

## ToC

- [Notify](#notify)

## Notify

Send notification using n8n webhook (Needs n8n workflow configured in advance)

### Inputs

| Name         | Description                                  | Example        | Required |
| :----------- | :------------------------------------------- | :------------- | :------: |
| **target**   | Where to send the message                    | "discord"      |   :o:    |
| **identity** | The identity (Bot) used to send the message. | "github"       |   :o:    |
| **content**  | Message to send                              | "test message" |   :o:    |

### Secrets used

| Name                         | Description             |
| :--------------------------- | :---------------------- |
| **NOTIFICATION_WEBHOOK_URL** | n8n webhook URL         |
| **WEBHOOK_BASIC_AUTH**       | n8n webhook credentials |
