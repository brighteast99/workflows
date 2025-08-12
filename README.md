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

### Secrets

| Name     | Description             |
| :------- | :---------------------- |
| **auth** | n8n webhook credentials |
