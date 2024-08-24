# <img src="images/wavesbicon2.ico" alt="Logo" width="35" height="35"> WaveSB Documentation

## Structure For Registering Commands

All scripts and custom commands for WaveSB must be written in Python. It's important to note that you cannot use the default Discord.py command registration methods, such as `client.command` or `bot.command`. Instead, you should follow the specific method provided by WaveSB for creating and registering custom commands.

| **Function**                                | **Parameter**                         | **Description**                                                |
|---------------------------------------------|---------------------------------------|----------------------------------------------------------------|
| `register_command(`                         | `"Category"`                          | The category under which the command will be listed.           |
|                                              | `"Command Name"`                      | The name of the command that users will type to execute it.    |
|                                              | `function_to_the_command`                | The function that will be executed when the command is called. |
|                                              | `"The Command's Description"`               | A brief description of what the command does.                  |
| `)`                                         |                                       |                                                                |

## Example

```python
register_command("Utilities", "ping", ping_command, "Checks the bot's latency.")
```

## Structure For Registering Events

All events for WaveSB must be made using the `reigster_event` function. Here's the structure.

| **Function**                                | **Parameter**                         | **Description**                                                |
|---------------------------------------------|---------------------------------------|----------------------------------------------------------------|
| `register_event(`                         | `"Event Name"`                          | The name of the event to listen for (e.g., on_message).           |
|                                              | `function_tho_the_event`                      | The function that will be executed when the event is triggered.    |
| `)`                                         |                                       |                                                                |

## Example

```python
register_event("on_message", message_event_handler)
```

