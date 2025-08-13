# WindPress – Blocksy Theme Bug Reproduction Demo

This repository contains a reproducible WordPress Playground demo showing how WindPress breaks the Blocksy product grid (WooCommerce `[products]` shortcode) when the plugin is active.

---

## Steps to reproduce with Playground demo

1. **Download** the demo ZIP from my repo:  
   <https://raw.githubusercontent.com/Abdul-Hanif/windpress-blocksy-bug/main/wordpress-playground-windpress-blocksy-bug.zip>
2. Visit <https://playground.wordpress.net>.  
3. Click ⋮ Menu → Import from .zip.
4. Login as admin, My account → Username: "admin" | Password: "password"
5. Go to the homepage.
6. You should see the broken product grid.
7. To fix this go to Plugins > Deactivate "WindPress".
8. Now when you go back to the homepage you should see the product grid displaying normally (demonstrating that WindPress is causing the broken product grid issue).
