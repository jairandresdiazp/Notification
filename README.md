# Notification
Send notification from shell

# Usage

```shell
fcm fcm <user> -t <title> -b <body> -i <icon> -c <click_action>
```
# Options

- -v, --version                      output the version number
- -u, --url <url>                    specifies the URL that processes the notification
- -k, --key <key>                    specifies the KEY of URL that processes the notification
- -t, --title <title>                specifies the parameter title of the notification
- -b, --body <body>                  specifies the parameter body of the notification
- -i, --icon <icon>                  specifies the parameter icon of the notification
- -c, --click_action <click_action>  specifies the parameter click_action of the notification
- -h, --help                         output usage information

# Commands

## send [options] <user>              send a notification to a specific customer

## Usage

send [options] <user>

## Options

- -v, --version                      output the version number
- -u, --url <url>                    specifies the URL that processes the notification
- -k, --key <key>                    specifies the KEY of URL that processes the notification
- -t, --title <title>                specifies the parameter title of the notification
- -b, --body <body>                  specifies the parameter body of the notification
- -i, --icon <icon>                  specifies the parameter icon of the notification
- -c, --click_action <click_action>  specifies the parameter click_action of the notification
- -h, --help                         output usage information

## Examples:

```shell
fcm send de20eecb-fd22-4d0b-b5f9-45a7379bd55d -u 'URL process notificacion' -t 'title of the notification' -b 'body of the notification' -i 'URL icono'
```

```shell
fcm send de20eecb-fd22-4d0b-b5f9-45a7379bd55d -u 'URL process notificacion' -k '4d0b-b5f9' -t 'title of the notification' -b 'body of the notification' -i 'URL icono'
```

```shell
fcm send de20eecb-fd22-4d0b-b5f9-45a7379bd55d -u 'URL process notificacion' -t 'title of the notification' -b 'body of the notification' -i 'URL icono' -c 'URL action'
```
