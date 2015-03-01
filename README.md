# Live templates for Twig to use in PhpStorm

## Installation
### Step 1
To install the live template file issue the following command:

```bash
curl -o ~/Library/Preferences/WebIde80/templates/Twig.xml \
https://raw.githubusercontent.com/rtuin/phpstorm-livetemplates-twig/master/Twig.xml
```
Where `WebIde80` stands for PhpStorm 8. More info can be found in the [JetBrains PhpStorm documentation](https://www.jetbrains.com/phpstorm/help/live-templates.html#d766914e117)

### Step 2
Restart PhpStorm

## Templates and usage

### Translation template

**Alias:** `trn`

**Produces:** `{{ '<cursor-ends-here>' | trans }}`

### Block creation

**Alias:** `block`

**Produces:**
```
{% block $START$ %}
$END$
{% endblock %}
```

## Contributing
Contributions are more than welcome. Issue a pull-request for your contributions.

## License
Please refer to the LICENSE.md file.
