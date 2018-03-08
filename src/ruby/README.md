# Converting JSON to YAML and/or YAML to JSON

Ruby one liner.

## USAGE


JSON to YAML (stdout)

```
$ ruby -ryaml -rjson -e 'puts YAML.dump(JSON.load(ARGF))' < example.json
```

JSON to YAML (redirect to file):

```
$ ruby -ryaml -rjson -e 'puts YAML.dump(JSON.load(ARGF))'< example.json > example.yml
```

YAML to JSON(stdout):

```
$ ruby -ryaml -rjson -e 'puts YAML.dump(JSON.load(ARGF))'< example.yml
```

YAML to JSON(redirect to file):

```
$ ruby -ryaml -rjson -e 'puts YAML.dump(JSON.load(ARGF))'< example.yml > example.json
```
