# AnmolAahar — Bowl & Beyond

Responsive front-end website prototype based on the supplied visual references. Open `index.html` in a browser to preview it. It uses a premium burgundy, gold, and cream palette, food-led sections, 24 illustrative menu items, veg/non-veg switching, and WhatsApp ordering links.

## Details to replace before launch

- **WhatsApp and phone:** The supplied number 9045504262 is configured centrally in `index.html` as `919045504262` for WhatsApp and displayed as `+91 90455 04262`. All WhatsApp CTAs and telephone links use these values.
- **Brand logo:** The supplied AnmolAahar logo is included at `assets/logo.jpeg` and appears in the header and footer. The header uses a matching burgundy background.
- **Social link:** Replace the Instagram placeholder link with the brand's profile URL.
- **Menu:** The 12 vegetarian and 12 non-vegetarian items in the `menus` object follow the supplied menu JSON. Cards show proposed prices, 350 g serving weights, and estimated calories, protein, carbohydrates, fat, and fibre. The page includes a visible nutrition disclaimer; confirm nutrition against standardized recipes before making definitive claims.
- **Images:** The hero uses the included original image at `assets/hero-salad.png`. Menu and custom bowl photos are illustrative Unsplash images, not confirmed photos of the listed recipes; fonts also load from Google Fonts. Replace remote photos with licensed, accurate brand photography for production.

## WordPress / Elementor handoff

This deliverable is a standalone front-end prototype, not a connected WordPress site or Elementor export. Its sections map cleanly to Elementor containers and reusable widgets: sticky header, hero, proof strip, menu grid, Why Choose Anmol Aahar benefits section, Build Your Healthy Habit and Why We Started sections, ordering steps, delivery areas, and footer. The menu records and central WhatsApp setting are deliberately grouped in the script to make migration into editable WordPress fields straightforward.
