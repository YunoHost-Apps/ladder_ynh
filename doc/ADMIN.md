This application downloads a binary from Ladder's GitHub repository and runs it on the YunoHost server as a systemd daemon. It is then connected to an nginx reverse proxy.

The binary is located in `__INSTALL_DIR__`.

The app uses the default ruleset : https://github.com/everywall/ladder-rules/blob/main/ruleset.yaml

To change the ruleset, you need to reinstall the app and change the URL when asked.