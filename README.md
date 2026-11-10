# Morning Sports Digest

A one-page daily digest of score cards for rugby, American football and baseball. It updates every morning at 07:17 JST.

**Live page:** https://oreos2007.github.io/morning-sports-digest/

## What's on it

- **Rugby**
  - 国内 (Japan): League One, university rugby and the Hanazono high school tournament and its qualifiers, written in Japanese.
  - International: test matches and the European leagues.
- **American Football:** NFL and ranked college games.
- **Baseball:** MLB and NPB results.

Each card shows both teams and the score. Teams have their logo, or a badge in their shirt colours if no logo is available. A chip appears when a result changed a team's league position.

## How it updates

A scheduled Claude Code Routine runs each morning. It searches for the last 24 hours of results, rebuilds `index.html` and commits it here. The whole page is one self-contained HTML file, with logos embedded.

Team names and logos are trademarks of their respective owners. This is a personal, non-commercial digest.
