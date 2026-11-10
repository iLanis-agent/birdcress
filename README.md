# Birdcress 1.0 TEST
Native Android Wataridori region-pairing puzzle. Android 8+ (min26), target35. Package com.gg007.birdcress. Twelve original unique boards on a 4x3 grid.

## Rules
Wataridori on a 4x3 grid with three outlined countries. Pair all six circles using horizontal/vertical links between neighboring cell centers. Each circle has exactly one link; used non-circle cells have two. Paths never share cells, cross, branch or loop. A numbered circle states the number of countries visited by its path, including the starting and ending countries. Two numbered partners must have the same number. Blank circles are wildcards and can pair with numbered or blank circles. A path cannot return to a country after leaving it; different paths may visit the same country. Unused cells are allowed. Tap gaps between neighboring cells to add/remove links. Twelve original uniquely solved room layouts; undo/reset, levels and saved palette/optional room letters. Known Wataridori adaptation.

## Download and status
https://mega.co.nz/#!wJVAUDAS!TVTs0TJ46nC8OZjjnzVT5dtF10r9kuK07wUUtW36biU
APK SHA256 1a46093f90fab8b27770d281c6c1f13a0c087025419f0cb1850c130d990894bb; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous downloaded bytes match. No requested permissions. Original icon unchanged.

## Checks
Portable seed-751110 generator enumerates all 131,072 edge states, groups legal three-path forests by endpoints and filters room visits with optional wildcard labels. It finds twelve distinct uniquely solved room layouts and completions from 23 connected four-cell partitions in 29 attempts. Independent oracle uses disjoint-set forests and separate within-country connectivity; production walks paths and tracks room transitions. All 1,572,864 complete edge states plus 120,000 randomized/invalid clue-room cases agree. Bounds, undo/replay/reset and solved lock pass. Actual drawing-adapter edge-midpoint taps solve all twelve and check menu, privacy, levels, next and saved palette/room letters/completion. Seven drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Reviewed all 206 live studio descriptions and the 803-entry web registry for Wataridori, wildcard circle pairing and exact room-visit counts. No functional match. Ribbonmere connects fixed pairs and covers all cells. Zigcress pairs anonymous circles but covers all cells and requires turns in every non-circle. Entryfern is a single all-cell route with room-entry ordinals. Birdcress instead pairs wildcard/numbered circles with exact country counts and no country re-entry, allowing unused cells and ordinary turns or straights. Known Wataridori adaptation; original generated layouts, code and visuals, not a global invention. Six supporting sources cover rules libraries, primary academic specification, playable implementation and publisher background. No source puzzle layouts, code or art copied.
Rules https://www.janko.at/Raetsel/Wataridori/index.htm ; independent rules https://www.cross-plus-a.com/html/cros7watr.htm .

## Build
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/blue-test src/com/gg007/birdcress/Board.java BoardTest.java then java -cp /tmp/blue-test com.gg007.birdcress.BirdBoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret is included.

## Privacy and branding
Birdcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, optional room letters and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 original icon, menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative 207-card studio and published catalog/studio sources and updater privately preserved at https://files.instinct.com/f7amwz7ywb9e-birdcress-source-archive . Repository https://github.com/iLanis-agent/birdcress holds README only; full Git source commit pending. Existing Jekyll static includes retained without changes; no Pages settings changes or client loader. Both site publications verified separately.
