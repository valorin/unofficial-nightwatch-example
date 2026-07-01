# laravel-official/nightwatch

See: https://securinglaravel.com/security-tip-have-you-heard-of-slopsquatting/

> ## ⚠️ Disclaimer — Demonstration package
>
> This is a **demonstration / placeholder package** created for **educational and
> security-awareness purposes only**.
>
> It is **NOT** affiliated with, endorsed by, sponsored by, or associated with
> **Laravel**, **Laravel Nightwatch**, the Laravel team, or Taylor Otwell in any way.
>
> The `laravel-official/nightwatch` name is intentionally official-looking to
> illustrate how convincing vendor and package names can be registered on public
> registries such as [Packagist](https://packagist.org). It exists to raise
> awareness of typosquatting and software supply-chain risks — please do not
> mistake it for a real Laravel product.

## What it does

**Nothing.** This package is intentionally inert: it ships no functional code and
registers no Composer scripts or plugins, so installing it executes nothing on
your machine. It exists purely as a companion artifact to a blog post about
software supply-chain and typosquatting risks.

> **Why it's inert:** Even setting aside that this package declares no scripts,
> Composer only runs a package's `scripts` for the **root** project — a
> *dependency's* scripts never execute on the consumer's machine. Getting a
> dependency to auto-run code at install time would require a Composer *plugin*
> (`type: composer-plugin`), which this package deliberately does **not** ship.

## License

MIT
