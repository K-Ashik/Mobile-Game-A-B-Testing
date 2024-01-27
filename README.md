# Mobile Games A/B Testing: Cookie Cats Project Overview

## Introduction
This project focuses on analyzing the results of an A/B test conducted on the mobile game "Cookie Cats." The A/B test involved moving the first gate in the game from level 30 to level 40 and observing its impact on player retention.

## Dataset
- The dataset contains information on 90,189 players who installed the game during the A/B test.
- Key variables include userid, version (gate_30 or gate_40), sum_gamerounds, retention_1, and retention_7.

## Analysis Steps
1. **Sanity Check**: Ensured roughly equal distribution of players in each AB group.
2. **1-Day Retention Comparison**:
   - Overall 1-day retention: ~44.5%.
   - 1-day retention slightly decreased with the gate moved to level 40.
3. **Bootstrapping for Confidence**:
   - Used bootstrapping to assess uncertainty in retention numbers.
   - Found strong evidence of higher 1-day retention with the gate at level 30.
4. **7-Day Retention Comparison**:
   - 7-day retention slightly lower with the gate at level 40.
5. **Bootstrapping for Confidence (7-Day Retention)**:
   - Confirmed higher 7-day retention with the gate at level 30.
   
## Conclusion
- Strong evidence indicates that both 1-day and 7-day retention are higher when the gate is positioned at level 30.
- Retention is a critical metric for player engagement and should be prioritized.
- The theory of hedonic adaptation suggests that forcing breaks with earlier gates prolongs player enjoyment.

## Future Considerations
- Other metrics like game rounds played and in-game purchases could be explored.
- Understanding player behavior and preferences can inform game design decisions for better user engagement.

---

Feel free to expand or customize this README with additional details or insights as needed!
