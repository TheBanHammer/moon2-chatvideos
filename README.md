# MOONMOON ChatVideo Bot

| Command     | Permission | Parameter | Description |
|-------------|------------|-----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| !cvdisable  | Moderator  |           | Disables all bot checks. |
| !cvenable   | Moderator  |           | Enables bot checks using settings. |
| !cvmaxviews | Moderator  | Integer   | Sets the maximum view count allowed before triggering notifications or timeouts. |
| !cvnotify   | Moderator  | String    | Tells the bot if it should post a chat message to notify the user. If a timeout is configured it will also inform the chat.<br><br>To enable use: enable/1/on<br>To disable use: disable/0/off |
| !cvstatus   | Moderator  |           | Prints a full status of the settings. |
| !cvtimeout  | Moderator  | Integer   | Sets the length of timeouts in seconds. Set to 0 to disable timeouts. |
| !ping       | Moderator  |           | Replies with chat message "Pong!" to ensure the bot is responding. |
