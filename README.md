# NeonAI Template TTS Plugin  # TODO: Name
[Mycroft](https://mycroft-ai.gitbook.io/docs/mycroft-technologies/mycroft-core/plugins) compatible
TTS Plugin for playing back static audio files. Plugin will look for a file whose name matches the requested
TTS string and play it back.

# Configuration:
```yaml
tts:
    module: neon-tts-plugin-audiofiles
    neon-tts-plugin-audiofiles:
      audio_file_path: /home/$USER/tts_audio_files
```