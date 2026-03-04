# Skills

Claude skills for personal use.

## my-boat

Reference profile for the Bavaria Cruiser 36 (2011) — vessel details, engine specs, sailing area, and maintenance notes. Used to tailor Claude's advice to the specific boat and Scottish waters.

### Install

Drag `my-boat.skill` into Claude.ai → Settings → Skills.

### Edit

Edit `my-boat/SKILL.md` directly, then repackage:

```bash
python -m scripts.package_skill ./my-boat ./ 
```

(Requires the skill-creator scripts from Claude Code / Cowork.)
