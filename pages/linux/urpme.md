# urpme

> Uninstall packages in Mageia.
> See also: `urpmi`, `urpmi.update`, `urpmi.addmedia`, `urpmi.removemedia`, `urpmf`, `urpmq`.
> More information: <https://wiki.mageia.org/en/URPMI#urpme>.

- Uninstall a package:

`sudo urpme {{package}}`

- Uninstall orphan packages (note: use it with caution as it might unintentionally remove important packages):

`sudo urpme --auto-orphans`

- Uninstall a package and its dependencies:

`sudo urpme --auto-orphans {{package}}`
