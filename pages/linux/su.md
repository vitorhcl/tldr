# su
> Run a command as a different user and group ID. Part of `util-linux`.
> See also: `sudo`.
> More information: <https://manned.org/su.1>.

- Run an interactive shell as root:

`su`

- Run an interactive shell as a specific user:

`su {{user}}`

- Run a login shell as root preserving most of the environment variables:

`su -`

- Run the specified shell:

`su --shell {{/bin/zsh}}`
