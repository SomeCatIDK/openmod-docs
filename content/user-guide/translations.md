# Translations

Translations files allow you to translate or customize OpenMod or plugin messages.  
OpenMod's translation `openmod.translations.yaml` can be found inside the `OpenMod` directory:
```yaml
commands:
  openmod:
    restricted: "This command is restricted."
  errors:
    out_of_range_error: "Too few arguments: missing parameter at index {Index} of type {Type.Name}"
    parse_error: "Parse error: could not parse {Value} to {Type.Name}"
    not_found: "Command was not found: {CommandName}"
    wrong_usage: "Wrong command usage. Correct usage: {Command} {Syntax}"
```

!!! Note
    Translation files are currently not updated automatically. If OpenMod or a plugin adds a new translation, you will have to add it manually to the yaml file or delete the file so it gets recreated.