# Protein Tracker V5 — Correct Units

The nutrition model now uses a reference quantity instead of assuming every food is per 100 units.

Defaults:
- Large egg: 1 piece = 6.3 g protein, 72 kcal, 0.4 g carbs, 4.8 g fat.
- Whey protein: 1 scoop = 24 g protein, 112 kcal, 1.3 g carbs, 1.2 g fat.
- Other gram/ml foods continue to use 100 g/ml as their reference.

Whey values are based on a representative Optimum Nutrition Gold Standard serving; the exact nutrition should be edited to match your own whey label.

Food add/edit forms now include a reference quantity so custom piece/scoop foods work correctly.

Upload all files to the root of the existing GitHub Pages repository.
