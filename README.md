 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/README.md b/README.md
index 0594850df9c0c343697f05150633da17f79c240e..5526d0aa3c15aafb0e97d7d4a608a80e8c7e2bd9 100644
--- a/README.md
+++ b/README.md
@@ -1,2 +1,15 @@
 # MineMod
-MineMod helps players create custom modpacks easily. Choose the mods you want, click download, and get a ready-to-install pack for your game version. All mods are compatible and organized in one folder to save time.
+
+MineMod is a frontend-only modpack helper website.
+
+## Features
+
+- Dark gaming UI built with plain HTML + CSS.
+- Select Minecraft mods with checkboxes.
+- Download selected mods in one click as a `.mrpack` archive.
+- No backend required.
+- Compatible with GitHub Pages.
+
+## Run locally
+
+Open `index.html` directly in your browser, or serve this folder using any static server.
 
EOF
)
