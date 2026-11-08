# Recruiter Claude Skills

Free [Claude](https://claude.ai) skills for recruiters, by [Bridgeway Talent Partners](mailto:will@bridgewaytalentpartnersai.com), a recruitment agency.

## Free skill: Boolean sourcing

`skills/sourcing-candidates-with-boolean` turns a job spec into search strings you can paste straight into LinkedIn, Google or a CV database:

- three strings, tight to wide, sized for your tool
- a Google X-ray string (with the minus-sign fix, because Google ignores NOT)
- the other titles and spellings real candidates use
- where else to look, including trades who aren't on LinkedIn

## Install

**Claude.ai (free or paid plan)**
1. Download this repo as a ZIP (green **Code** button → **Download ZIP**) and unzip it.
2. Zip the `sourcing-candidates-with-boolean` folder on its own.
3. In Claude: **Settings → Capabilities**, turn on **Code execution and file creation**.
4. **Customize → Skills → Upload skill**, and pick the zip.
5. New chat: *"Here's a job spec, build me Boolean strings for LinkedIn."*

**Claude Code**
```bash
cp -r skills/sourcing-candidates-with-boolean ~/.claude/skills/
```

**Any other AI chat**: open `SKILL.md`, copy everything below the second `---`, paste it into a chat, then add your job spec.

## Want the full set?

**[The Recruiter's Claude Kit](https://velocitybrand.gumroad.com/l/iprdfx)**: 9 skills covering the whole placement. Role scorecards, outreach with follow-ups, fair CV screening, client submissions, interview prep, placement aftercare, winning clients and going freelance. Includes a setup guide and our 23-page ebook.

**[The Solo Recruiter's AI Playbook](https://velocitybrand.gumroad.com/l/azgvg)**: the ebook on its own.

## Run an agency? We'll wake up your candidate database

Velocity Branding (the team behind these skills) runs email for independent recruitment agencies: candidate reactivation, job alerts and client business development. The first 3-email reactivation sequence is free, written for your niche. [See how it works](https://velocitybrandinginc.com/recruitment-email-marketing).

## Use it responsibly

Remove ID numbers, addresses, dates of birth and photos before pasting CVs into any AI tool. Follow your local data law (POPIA, UK GDPR, GDPR). Check every result before you use it.

## License

MIT. Use it, change it, share it.
