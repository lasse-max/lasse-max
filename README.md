# Lasse

I build products that help people make decisions.

## Sextant

**Find the right roles early. Put your time into landing them.**

Keeping up with new vacancies means checking company sites, repeating searches, and reading roles that only look relevant from their titles. That effort competes with the work that makes a candidate stronger: preparing for interviews, building skills, and writing thoughtful applications.

Sextant takes on the daily discovery work. In its current live setup, it scans a pool of **6,000+ roles every day** and delivers relevant opportunities to the inbox. Matching draws on a configurable company priority list, career background, skills, and practical constraints to explain why a role deserves attention.

The companion app turns those recommendations into action: clear fit bands help prioritise the list, evidence highlights strengths and gaps to address in an application, and a tracker keeps the next steps organised.

**Live and in active testing.** The next ambition is an open-source setup that lets other candidates configure and run a search around their own goals.

**Inside Sextant:** an app screenshot captured on 8 September 2026, plus an email excerpt from 4 September. Counts and recommendations are snapshots of the displayed runs. The operational app remains owner-only because it contains personal job-search data.

![Sextant scan overview showing 7,527 postings and recommendations grouped into apply, consider and stretch](assets/sextant/scan-overview.png)

*From the scanned catalog to a prioritised set of opportunities.*

<details>
<summary>See the email digest</summary>

![Sextant email digest excerpt showing the scan summary, source issue count and a scored recommendation](assets/sextant/email-digest.png)

*The inbox digest brings together scan results, source-health signals and an explanation of role fit. This excerpt omits the email headers and personal eligibility details.*

</details>

**Built with:** Python, Claude, Next.js, TypeScript, Supabase Postgres, GitHub Actions, Resend, and Vercel.

## Movie Match

**Bring the fun back to movie night.**

You sit down together to watch a film. Half an hour later, you're still switching apps, scrolling past recommendations, and asking, “What about this one?” Each service offers a different slice of the film catalog and a different idea of what you might like. Choosing becomes the evening.

Movie Match brings the search across streaming services into a playful game for two people sharing one phone. Recommendations start with **tonight's mood and the person beside you**. In a game designed to take under three minutes, you choose your moods, react to films, and pick from a shortlist of films you can stream tonight. You land on one you both picked, with where to watch it.

https://github.com/user-attachments/assets/2f0a2710-3e80-4398-8917-0559a1a69a93

*The 2.0 video, 61 s with sound: a full game with two demo players, and what happens behind the scenes.*

**Behind the scenes**

- **Your taste, mapped.** Over 15,000 films are stored as embeddings. Each player's likes become a taste fingerprint, and the search looks near both of you, including where your tastes meet.
- **Built for both of you.** AI plans the search from both players' moods and ranks both lists together, so a match isn't left to luck.
- **Only what you can stream.** Every film is checked in code against your services in your region. The AI never decides availability.
- **Tested before it ships.** Matching changes run against 17 frozen test couples and an independent AI judge, with the pass bars committed before each run. When a bar fails, the [results](https://github.com/lasse-max/movie-match/blob/main/eval/e4-results.md) say so.

**Now in beta, with 2.0 rolling out:** catalogue search went live on 7 November 2026. Focused user testing is generating strong early feedback as the product moves towards launch.

[Try the beta](https://movie-match-rho.vercel.app) · [See how it works](https://github.com/lasse-max/movie-match)

<p>
  <img src="assets/movie-match/setup.jpg" width="220" alt="Movie Match setup: choose a region and streaming services" />
  <img src="assets/movie-match/swipe.jpg" width="220" alt="Movie Match swipe round: react to a film with Not it, Not sure or This vibe" />
  <img src="assets/movie-match/match.jpg" width="220" alt="Movie Match result: the film you both picked, with its match score and where to watch it" />
</p>

*Screens from a demo game on the live beta on 10 November 2026, with two made-up players. Titles and availability reflect that session.*

**Built with:** Next.js, React, TypeScript, Tailwind CSS, Claude, embeddings, Supabase Postgres with pgvector, TMDB, and Vercel.

## Training Coach

A personal workout tracker that uses logged sets to calculate the next session’s exercises, reps and load targets. Built for use on a phone, with offline session logging and progress tracking.

**In development.** The core tracker is implemented; deployment and reliability work are still in progress.

**Built with:** Python, FastAPI, JavaScript, Supabase Postgres, and Vercel.

## How I work

I define the product requirements, shape the user experience, and test the results. I use AI assistants for implementation and review.

## Contact

[Email](mailto:lassekrgr@gmail.com)
