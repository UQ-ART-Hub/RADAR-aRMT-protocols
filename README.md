# Protocols

Each directory contains the protocol for each of the corresponding ART-Hub RADAR-Base projects, defined within the Management Portal <https://arthub-radarbase.cloud.edu.au/managementportal/#/>. 

The documentation on the protocol structure can be found within the ART-Hub MS Teams, or on <https://radar-base.github.io/RADAR-aRMT-protocols/>.


## Protocol validation

The protocol format is described by a JSON Schema, in docs/protocol-schema.json. The current version of the format is 0.0.2. All protocols in this repository should follow that schema. A technical way to achieve this, is by JSON Schema validation.

Protocol validation requires Bash and [Yarn](https://yarnpkg.com/lang/en/docs/install). To validate the protocols in this directory, run
```shell
./validate
```

