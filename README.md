# ExtDNS

[English](./README.md) | [简体中文](./README-zh-CN.md)

![License](https://img.shields.io/github/license/dntsk/extdns)

ExtDNS synchronizes labeled records in docker-compose with DNS providers.

Inspired by [External DNS](https://github.com/kubernetes-sigs/external-dns), ExtDNS makes resources discoverable via public DNS. It retrieves a list of records from Docker's labels and creates it in public DNS.

- ExtDNS uses the `/var/run/docker.sock` to query DNS records defined in container labels and then creates these records in public DNS.
- Supports custom DNS IP address in labels, such as private IP address.
- Provides an option to automatically detect public IP and use it as DNS record.
- Automatically updates DNS records when IP address changes.
- Automatically removes DNS records when containers are deleted.
- Checks for changes every 300 seconds by default.

## Docs

All the docs placed in [docs](https://github.com/dntsk/extdns/tree/master/docs) folder.

Also you can view it on [official website](https://extdns.dntsk.dev).

## Contribute

If you want to report a bug or request a new feature. Free feel to open a new issue or pull request.

English proofreading is needed too, because my grammar is not that great sadly. Feel free to correct my grammar in this Readme or source code.

## License

This project is licensed under the [MIT License](./LICENSE).

If you find this project useful for you, please consider giving us a ⭐.
