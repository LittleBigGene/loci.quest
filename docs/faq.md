# FAQ

## What is Loci?

Loci is a web-based memory palace for CAS exam study. Each exam becomes an explorable **estate** with **domain wings** and **task rooms** where you interact with exam material through point-and-click scenes rather than flat outlines.

## Which exams are supported?

**CAS Exam 6U (US)** is the current focus. **6C (Canada)** is planned next. See [exam-coverage.md](exam-coverage.md) and [roadmap.md](roadmap.md).

## How much does it cost?

Two tiers per exam track, starting with **6U**:

| Tier | Price | Estate | Noriko |
|---|---|---|---|
| **Estate** | **$199** | Lifetime | — |
| **Estate + Noriko** | **$599** | Lifetime | 1 year unlimited Q&A from purchase |

**Renew Noriko:** **$149/year** for another year of unlimited Q&A.

**Already have Estate?** Add Noriko for **$399** (first year), then **$149/year** to renew — same total as **Estate + Noriko** ($199 + $399 ≈ $599).

## How long does access last?

**Estate access is lifetime** on both tiers — the memory palace, wings, rooms, curated readings, and progress sync do not expire.

**Noriko** is included for **1 year** of **unlimited Q&A** from when you first activate it (whether bundled in **Estate + Noriko** or added after **Estate**). After that, you keep full estate access; renew for **$149/year** when the purchase flow supports it.

## Who is Noriko?

**Noriko** is Loci's AI exam tutor. She answers questions using the indexed readings for your track — with page and document citations — not generic ChatGPT. Unlimited Q&A means no per-message caps during your active Noriko period.

## What's the difference between Estate and Estate + Noriko?

**Estate** ($199) is the core product — explore the memory palace, unlock wings and rooms, read curated syllabus material, and sync progress across devices. No Noriko.

**Estate + Noriko** ($599) includes **lifetime estate access** plus **1 year of unlimited Q&A with Noriko**. Chat requires an active Noriko entitlement for that track.

## Can I upgrade from Estate to Noriko?

Yes. If you bought **Estate** ($199) first:

| Step | Price |
|---|---|
| Add Noriko (first year) | **$399** |
| Renew Noriko (each year after) | **$149** |

That matches **Estate + Noriko** upfront ($199 + $399 ≈ **$599**). Upgrade and renewal checkout will launch with **loci.api** + Stripe; contact support if you need help before then.

## Do I need to install anything?

No. Loci runs in the browser. A PWA with offline revisits is planned; there is no native app requirement today.

## Does my progress sync across devices?

Not yet. Progress is stored locally in your browser for now. Account sync is planned via a future backend (**loci.api**).

## What browsers are supported?

Modern evergreen browsers (Chrome, Firefox, Safari, Edge). If something breaks, please [file an issue](https://github.com/LittleBigGene/loci.quest/issues) with your browser and OS.

## Is Loci open source?

No. The app source lives in a private repository. This public repo (**loci.quest**) is for product information, documentation, and support.

## How is content authored?

Exam content — estates, wings, rooms, landmarks, and puzzles — is curated for accuracy. Room design uses AI assistance for brainstorming and copy; all material is reviewed for exam correctness before release.

## I found an error in exam content

Please [open an issue](https://github.com/LittleBigGene/loci.quest/issues) with the room or domain, what looks wrong, and a reference (syllabus section, source reading, or CAS material) if you have one. Content corrections are a priority.
