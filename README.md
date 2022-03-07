# OpenBar wizard

The `wizard` is a powerful tool that allows you to create your OpenBar projects
in no time.

## Usage

The `wizard` is a simple script that can be run from the network using this
shell one-liner:

``` bash
T=$(mktemp) && curl -sL https://openbar.github.io/wizard/wizard -o ${T} && sh ${T}
```

You will then be asked a few questions to set up your initial repositories.

Once created your repositories can be pushed to your favorite git server.

## Further Reading

For more information about the OpenBar project, the specifications of
the `openbar` build system, and to discover some examples, please visit
the project documentation:

> https://openbar.github.io

## License

The `wizard` is released under the [MIT License](LICENSE.md).
