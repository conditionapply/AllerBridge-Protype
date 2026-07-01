# AllerBridge — Working Prototype

**Travel hungry, not worried.**

A safety-first travel food-allergy **communication and decision-support** app for
international travelers, study-abroad students, and families with food allergies.

> ⚠️ **Safety framing (important).** AllerBridge is a communication and decision-support
> tool. It does **not** guarantee that food is allergen-free and never labels a dish
> "safe." Every result points you back to confirming with restaurant staff. A menu photo
> shows dish *names*, not hidden ingredients, oils, sauces, or cross-contact — so the app
> helps you *ask the right questions* instead of giving a false "safe" verdict.

---

## How to open it

**Just double-click `index.html`.** It opens in any modern browser (Chrome, Safari, Edge, Firefox).

Everything — the design and all the logic — is contained inside that **one file**. There
are no separate stylesheet or script files to load, so it works even if you move or email
just the `index.html`. No installation, no internet, no accounts, no API keys, no backend.

---

## Files included

| File | Purpose |
|------|---------|
| `index.html` | The entire app — all 8 screens, design, and logic in one self-contained file |
| `README.md` | This file |

Your selections (allergens, severity, destination, card language) are saved in the
browser so they persist while you use — and after you reload — the app.

---

## Best demo flow

Follow the bottom navigation left-to-right:

**Home → Profile → Travel → Chef Card → Menu → Guide → SOS → Info**

1. **Home** — landing screen, slogan, and the safety notice.
2. **Profile** — pick allergens (try *Peanuts* + *Sesame*), set severity and cross-contact sensitivity. These choices drive everything else.
3. **Travel** — choose a destination (try *Mexico*). Language, emergency number, sample menu, and phrases all localize.
4. **Chef Card** *(hero feature)* — a translated, allergen-specific card to show staff. Switch languages; tap **Present Full-Screen Card** to hand your phone to a server.
5. **Menu** — tap **Generate Questions**. It's a *helper*, not a "safe-food scanner": watch the scan animation, then it reads the sample menu. You can also upload a menu photo.
6. **Guide** — results grouped by concern level, each with a ready-to-ask staff question:
   - 🔴 **Possible concern** — an allergen you selected appears in the dish.
   - 🟡 **Hidden-risk question** — the name is clear but sauces/oils/broths often hide allergens.
   - 🔵 **No obvious match — still verify** — nothing obvious, but confirm anyway.
   - There is **no green "safe"** category, by design.
7. **SOS** — destination emergency number and translated emergency phrases.
8. **Info** — destination-specific hidden-risk food knowledge (e.g. mole hides peanuts/sesame; French pastries can be egg-washed).

---

## Supported in this prototype

- **Destinations (8):** Mexico, Japan, India, Thailand, Italy, UAE, France, Spain
- **Chef-card languages (8):** English, Spanish, Japanese, Hindi, Thai, Italian, Arabic, French
- **Allergens tracked (9):** Peanuts, Tree nuts, Milk, Egg, Wheat, Soy, Shellfish, Sesame, Fish

---

*Prototype built for the UDC Capital Cup entrepreneurship competition. Not a medical device.*
