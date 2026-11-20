<p align="center">
  <img src="assets/logo.png" alt="job-match logo" width="128" height="128">
</p>

# job-match — self-install edition

Made by **Caio Teixeira** · [LinkedIn](https://www.linkedin.com/in/caio-teixeira-espirito-santo/) · [GitHub](https://github.com/caio-t)

[Português](#português) · [English](#english)

---

## English

> [!CAUTION]
> **You install and use this edition entirely on your own, at your own risk.**
>
> - This is **not** the version in the Claude directory. It was **not reviewed by Anthropic** and is
>   not supported.
> - It drives **your own browser** (Claude in Chrome) to read your LinkedIn profile and job sites, and
>   it can read a page's internal data and call its undocumented endpoints. **LinkedIn, Indeed,
>   Glassdoor and other sites forbid automated access in their terms of use.** Using this edition may
>   break those terms and get your account limited or banned.
> - **You alone are responsible** for how you use it, for complying with each site's terms and with
>   the law where you live, and for any consequence. The author accepts **no liability** of any kind.
> - The software is provided **"as is", without warranty**, under the [MIT License](LICENSE).
>
> If you don't accept these terms, don't install it. Use the reviewed version on the
> [job-match](https://github.com/caio-t/job-match) repository instead.

### What's different from the directory version

| | [job-match](https://github.com/caio-t/job-match) (Claude directory) | job-match-self-install (this repository) |
|---|---|---|
| LinkedIn profile | You export it as PDF or paste it | Opened and read in your browser |
| LinkedIn / Indeed / Glassdoor | Only what search results show | Browsed with your session |
| JavaScript career pages | Public job feeds only | Reads page data (`__NEXT_DATA__`) and calls internal `/api` endpoints |
| Reviewed by Anthropic | Yes | No |
| Installs as a plugin | Yes | No: manual copy only |

### Install (manual, Claude Code only)

There is no one-click install on purpose. Download this repository
(**Code → Download ZIP** on GitHub) and copy the `skills/job-match` folder to `~/.claude/skills/job-match`. Then start a new Claude Code session.

The browser features need the Claude in Chrome extension. Don't install it next to the directory
version of the plugin: both are called `job-match`.

How it works and usage examples: see the [job-match README](https://github.com/caio-t/job-match#readme).

---

## Português

> [!CAUTION]
> **Instalas e usas esta edição por tua conta e risco.**
>
> - **Não** é a versão da loja do Claude. **Não foi revista pela Anthropic** e não tem suporte.
> - Usa **o teu próprio browser** (Claude in Chrome) para ler o teu perfil do LinkedIn e sites de
>   vagas, e pode ler dados internos das páginas e chamar endpoints não documentados. **O LinkedIn, o
>   Indeed, o Glassdoor e outros sites proíbem o acesso automatizado nos termos de uso.** Usar esta
>   edição pode violar esses termos e levar à limitação ou ao bloqueio da tua conta.
> - **És o único responsável** pela forma como a usas, por cumprir os termos de cada site e a lei do
>   teu país, e por qualquer consequência. O autor **não assume qualquer responsabilidade**.
> - O software é fornecido **"tal como está", sem garantias**, sob a [licença MIT](LICENSE).
>
> Se não aceitas estas condições, não a instales. Usa a versão revista do
> [repositório job-match](https://github.com/caio-t/job-match).

### Instalar (manual, só Claude Code)

De propósito, não há instalação com um clique. Descarrega este repositório (**Code → Download ZIP**
no GitHub) e copia a pasta `skills/job-match` para
`~/.claude/skills/job-match`. Depois abre uma sessão nova do Claude Code.

As funções de browser precisam da extensão Claude in Chrome. Não a instales ao lado da versão da loja
do plugin: as duas chamam-se `job-match`.

## License

MIT. See [LICENSE](LICENSE).
