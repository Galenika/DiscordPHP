# DiscordPHP
PHP API to use with Discord (WebHooks, Messages and RichEmbeds) 

## Examples
See examples [here](https://github.com/Guthen/DiscordPHP/tree/master/examples).

## Classes

### WebHook

#### Construct
```php
$webhook = new Discord_Webhook( $url = "" );
```

#### Methods

|        Methods          |       Description      |
|-------------------------|------------------------|
| `setURL( string $url );` | Change the Webhook URL | 
| `send( Discord_Message $msg );` | Send the Message/RichEmbed |

### Message

#### Construct
```php
$msg = new Discord_Message( $content = "" );
```

#### Methods

|        Methods          |       Description      |
|-------------------------|------------------------|
| `setContent( string $content );` | Change the Message content | 
| `setUsername( string $username );` | Change the Message username | 
| `setAvatarURL( string $url );` | Change the Message avatar URL | 
| `setTTS( bool $tts );` | Set whenever the TTS option is activated |
