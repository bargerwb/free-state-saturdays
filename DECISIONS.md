# Free State Saturdays — Decisions

Most recent wins. If something here contradicts older context, this is correct.

Last updated: February 11, 2026

---

## Project

- **What**: Landing page for Free State Saturdays, a monthly liberty gathering in Manchester, NH
- **Who runs it**: Manchester Freefellows (not FSP, not LPNH, not any official org)
- **Site**: https://free-state-saturdays.netlify.app
- **Netlify site ID**: e0ac4346-1103-4a20-beda-3904e9ba8bfc
- **Deploy from**: `site/` folder via Netlify REST API (file digest method)
- **Stack**: Single HTML file + Tailwind CDN. No frameworks, no build tools, no JS except Tailwind config.

## Event Details

- **When**: First Saturday of every month, 6:00 PM
- **Where**: 8025 S Willow St #205, Manchester, NH (AFP headquarters)
- **Cost**: Free. No RSVP, no ticket.
- **Food**: Always food. People encouraged to bring a dish. May be catered sometimes. Do NOT brand as "always a potluck."
- **Next event date**: Update `<!-- UPDATE MONTHLY -->` comments in index.html each month (appears twice: hero card + footer)

## Tone & Positioning

- **Confident, cheeky, unapologetic.** Not defensive. Not edgy for edgy's sake.
- **"Far right" label**: Lean into it as a filter/joke, don't fight it. "If that's far right, we'll wear it."
- **Target audience**: Normal libertarians. Millions of them. Not the weird fringe stereotype.
- **Do NOT** position attendees as "the weird ones in the room." Positioning is: your views are normal, you just don't have the room yet.
- **Solo consultant voice**: Bill uses "I" not "we" in his own work. FSS copy uses "we" because it's a community.

## Relationship to Other Orgs

- **FSP New Mover Potluck**: Technically still exists. Don't say it's dead. Cheeky shade is fine ("there are quiet clubhouses with aging potlucks and no kids"). FSP is currently mad at Freefellows for not being apologetic.
- **Carla Gericke**: Runs the potluck at The Quill. Don't name her. Don't engage.
- **LPNH, FSP, Jeremy Kauffman, Mayor of Manchester (Patrick Binder)**: All attend and are listed as social proof.
- **"Mayor of Manchester"**: Patrick Binder's joke/aspirational title, not actual elected mayor. Keep it — it's an in-group signal.
- **Tall Bill (@billisajoke)**: Listed as social proof.

## Design

- **Dark theme**: #0a0a0a background, gold/amber (#d4a017) accents
- **Font**: Inter via Google Fonts
- **Mobile-first**: Tailwind responsive prefixes
- **Photos**: Real event photos only. No stock. Currently 3 deployed (2 Super Bowl, 1 Christmas party). Raw archive in `raw-photos/`.

## Email Capture

- **Netlify Forms** with `data-netlify="true"`. Form name: "mailing-list"
- **Submissions**: https://app.netlify.com/projects/free-state-saturdays/forms
- **Backend for actual mailing list**: Not yet decided. Separate conversation.
- **Free tier**: 100 submissions/month

## What NOT to Do

- Don't promise "always free, always potluck"
- Don't explicitly say replacing FSP potluck
- Don't use outdoor/grill imagery (it's winter in NH, events are indoors)
- Don't attract the "weird libertarian" identity — attract normal people with normal opinions
- Don't use stock photos
