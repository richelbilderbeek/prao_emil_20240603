# PRAO of Emil

- When: June 3, 4, 5, 10, 11 (weeks 23 and 24)(see [schedule](schedule.md)),
  each day from 9:00-16:00
- Where in Uppsala: Biomedical Center, Husargatan:
  see [location](location.md) how to get there
- Where in BMC: [office B9:430b](https://use.mazemap.com/#v=1&zlevel=4&center=17.635980,59.841862&zoom=19.9&campusid=49&desttype=poi&dest=386656):
  see [office](office.md) how to get there
- [Schedule](schedule.md): see [schedule](schedule.md)
- [Report](report.md): see [report](report.md)
- [Reflection](reflection.md): see [reflection](reflection.md)

## PRAO goal

To find out how working life at NBIS/UPPMAX/UU is like.

## PRAO projects

Pick one:

- [ ] Find/write an example of well-written Python code
  that shows a run-time speed bottleneck
  at an unexpected location.
  Adapt text at <https://uppmax.github.io/programming_formalisms/optimisation/runtime_speed_profiles/>
- [ ] Do the exercises at <https://uppmax.github.io/programming_formalisms/optimisation/big_o/> ,
  add these to the course materials
- [ ] Finish the Programming Formalisms example project at <https://github.com/programming-formalisms/programming_formalisms_example_project>
- [ ] Convert some private notes to documentation on how to
  transfer data to Swestore

## FAQ for colleagues

### What is the purpose of meeting the PRAO student?

To show the diversity within our workplace.

The goal for the PRAO student is to find out how working at
university/NBIS/UPPMAX looks like. I (Richel) think that
we do widely different things and have widely different
opinions and personality. Hence, I hope the PRAO student
meets a lot of colleagues.

### What should I do with the PRAO student?

The goal of a PRAO is to find out how our working life
looks like.

You can already do so by having him come to your office and
talk about your job. You can also use the PRAO student
to do work you'd give to a new colleague.

### How do I book some time with the PRAO student?

In many ways:

- Send a Slack PM to Richel Bilderbeek
- Send an email to `richel.bilderbeek@icm.uu.se`
- Create an Issue at this repo
- Create a Pull Request to this repo,
  putting yourself in a slot in [the schedule](schedule.md)

### How long can I have the PRAO student?

At least one slot at most all slots in two days.

- One slot, because it allows for straightforward scheduling
- Two days, because it allows for meeting many colleagues

### Help, I must cancel last-minute

No worries, just let Richel or the PRAO student know.

## Files used by continuous integration scripts

Filename                              |Descriptions
--------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------
[mlc_config.json](mlc_config.json)    |Configuration of the link checker, use `markdown-link-check --config mlc_config.json --quiet docs/**/*.md` to do link checking locally
[.spellcheck.yml](.spellcheck.yml)    |Configuration of the spell checker, use `pyspelling -c .spellcheck.yml` to do spellcheck locally
[.wordlist.txt](.wordlist.txt)        |Whitelisted words for the spell checker, use `pyspelling -c .spellcheck.yml` to do spellcheck locally
[.markdownlint.jsonc](.markdownlint.jsonc)|Configuration of the markdown linter, use `markdownlint "**/*.md"` to do markdown linting locally. The name of this file is a default name.
[.markdownlintignore](.markdownlintignore)|Files ignored by the markdown linter, use `markdownlint "**/*.md"` to do markdown linting locally. The name of this file is a default name.
