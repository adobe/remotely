# Remotely

Remotely is an automation tool to run tasks in an AWS host

## First steps

Install awscli:

`brew install awscli`

Export AWS credentials

## Examples

`./remotely -f "proxy, master" -c "ls -l && uptime"`
`./remotely -f "proxy" -l 10.10.1.3`

## Contributing

Contributions are welcomed! Read the [Contributing Guide](CONTRIBUTING.md) for more information.

## Licensing

This project is licensed under the Apache V2 License. See [LICENSE](LICENSE) for more information.

## Author

Alejandro Sanchez Acosta <sancheza@adobe.com>
