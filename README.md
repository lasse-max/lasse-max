# Lasse

I build products that help people make decisions: what to watch together, which job opportunities deserve attention, and what to do next.

**Layline** is the home for that work. In sailing, a layline is the course from which you can reach the next mark without another tack. I use that idea as a product principle: define the destination, understand the constraints, and make the next decision easier.

## Selected work

| Product | The decision it helps with | Status |
|---|---|---|
| [Movie Match](https://movie-match-rho.vercel.app) | Turn the search for a film into part of the fun of movie night. | Beta 1.9 · focused user testing |
| [Sextant](#sextant) | Find relevant roles early and spend more time preparing to land them. | Live · active testing |

### Movie Match

**Bring the fun back to movie night.**

You sit down together to watch a film. Half an hour later, you're still switching apps, scrolling past recommendations, and asking, “What about this one?” Each service offers a different slice of the film catalog and a different idea of what you might like. Choosing becomes the evening.

Movie Match brings the search across streaming services into a playful game for two people sharing one phone. Recommendations start with **tonight's mood and the person beside you**. In a game designed to take under three minutes, you choose your moods, react to films, and discover a shortlist of up to five recommendations, with the services where you can watch them.

**Now in beta 1.9:** focused user testing is generating strong early feedback as the product moves towards launch.

[Try the beta](https://movie-match-rho.vercel.app) · [Explore the product and code](https://github.com/lasse-max/movie-match)

**Built with:** Next.js, React, TypeScript, Claude, TMDB, and Vercel.

### Sextant

**Find the right roles early. Put your time into landing them.**

Keeping up with new vacancies means checking company sites, repeating searches, and reading roles that only look relevant from their titles. That effort competes with the work that makes a candidate stronger: preparing for interviews, building skills, and writing thoughtful applications.

Sextant takes on the daily discovery work. In its current live setup, it scans a pool of **6,000+ roles every day** and delivers relevant opportunities to the inbox. Matching draws on a configurable company priority list, career background, skills, and practical constraints to explain why a role deserves attention.

The companion app turns those recommendations into action: clear fit bands help prioritise the list, evidence highlights strengths and gaps to address in an application, and a tracker keeps the next steps organised.

**Live and in active testing.** The next ambition is an open-source setup that lets other candidates configure and run a search around their own goals.

**Demo access:** the operational application is owner-only because it contains personal job-search data. A public walkthrough using sample data is planned; screenshots and a short video have not been added yet.

<!-- Add public demonstration assets here when ready. Suggested sequence:
1. Opportunity list, showing a small set of sample recommendations.
2. Role detail, showing evidence, fit, and limitations.
3. Shortlist and application tracker, showing the next action.
Optional: a 60–90 second narrated walkthrough.
Keep these assets in this public profile repository if the working Sextant repository is private.
-->

**Built with:** Python, Claude, Next.js, TypeScript, Supabase Postgres, GitHub Actions, Resend, and Vercel.

## How I work

I use AI assistants for implementation and review, with separate building and reviewing roles. My focus is the product problem, the user experience, the tradeoffs, and the evidence that a change improves the result.

- **Give models a bounded task.** Use them to interpret preferences or explain fit; keep factual checks and permissions in application code.
- **Test the difficult cases.** Divergent tastes, weak job matches, missing data, and failed external services reveal more than a smooth demonstration.
- **Keep people in control.** Make the recommendation understandable and leave consequential decisions with the user.

## Ideas for the future

LineupIQ, Invoice Genie, Portfolio Dispatch, and Dead Reckoning are ideas I plan to revisit. They are set aside for now while I focus on testing and developing Movie Match and Sextant.

## Contact

[Email me](mailto:lassekrgr@gmail.com) about the products, their design decisions, or opportunities to build useful tools.
