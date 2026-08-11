BEACON OF HOPE — NZ GALA LANDING PAGE
======================================

Files:
- beacon-of-hope-nz-landing.html  → the whole page (single file, no build step)
- assets/boh-logo.jpg             → logo (150px — replace with hi-res original when available)
- assets/kelly-photo.jpg          → Kelly Markey photo (from IG reel — replace with clean portrait if available)

Before going live:
1. Search the HTML for "YOUR-DOMAIN.com" (4 places, og:/twitter: meta tags)
   and replace with the real hosting domain, otherwise social shares show no image.
2. Add Meta Pixel + Google tag in <head>, and fire a conversion event on the
   Eventbrite button clicks (all "Book" buttons link to
   https://www.eventbrite.co.nz/e/beacon-of-hope-mission-awards-tickets-1994123498063).
3. Fonts load from Google Fonts (Roboto + Roboto Slab) — needs internet, no install.
4. Countdown targets 2026-08-29 18:00 NZST — hardcoded in the <script> at the bottom.
5. Brand colours are CSS variables at the top of the <style> block:
   Golden #C9A24A / #F2C14E (accents), Blue #00167B, Grey #58595B, Light grey #CBCBCB.

No frameworks, no dependencies — upload and it works.
