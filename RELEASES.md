# OpenTac engine releases

One entry per promotion of `stable`, newest first. Written by `promote.yml`; do not edit by hand.
Each entry is anchored by an immutable `stable-YYYY.MM.DD[-N]` tag on the engine refs.

<!-- releases:begin -->

## stable-2026.11.07 (2026-11-07)

- Upstream: main
- Commit range: `72eb3fd..73c14ac` (836 commits)
- Dependencies changed: yes
- Canary: 3 days
- Gate run: https://github.com/gonzoinceng-ctrl/opentac-engine/actions/runs/41818313185
- Minimum OpenTac version: 0.0.0
- Severity: normal

### feat

- `e80f583e` feat(awareness): add calm sonar pulses that flash the range ring and echo contacts
- `af461feb` feat(voice): add typed AI chat beside voice
- `d546d653` feat(kit): show the panel rails as labelled pills until a panel opens
- `fd4b69ff` feat(cockpit): teleport the shared Display groups into Cockpit's popover
- `4c92f517` feat(cockpit): render the utility strip's measured layout from the store
- `c3c69a91` feat(display): render the style parameters from the display store
- `3a750c90` feat(recording): render the safe frame from a recording store
- `0949f6a7` feat(location): render the search field's open and searching state from the tray
- `b4ee2321` feat(globe): answer both reset buttons through the globe actions store
- `eccaeea0` feat(globe): render the tilt and north-up buttons from the globe actions store
- `7edf8a57` feat(globe): answer the clear and share actions through the globe actions store
- `2e43bd99` feat(kit): render the remaining ranges with UiSlider
- `b9ecb9b9` feat(kit): render the status badges and empty states with UiBadge and UiEmpty
- `ecaf7230` feat(kit): render the selects with UiSelect
- `28ca784d` feat(kit): render the chips with UiChip and UiButton
- `d98a7c81` feat(kit): render the pressed toggles with UiButton
- `5019bd9e` feat(kit): render the sliders with UiSlider
- `fa2dc9fc` feat(radio): hand the tuner slider's events to RadioControls through the store
- `7f7e66e7` feat(radio): answer the internet radio controls through the radio store
- `61d11ce3` feat(radio): answer the RTL-SDR card through the radio store
- `e5fa31d0` feat(controls): render every segmented group with UiSegmented
- `42c3cc12` feat(import): render the file import in a GeoImport view
- `a6e85db8` feat(draw): answer the Draw controls through the display store
- `3c3f8e3e` feat(display): answer the Display controls through the store with UiSegmented
- `fc536821` feat(controls): render the action and toggle buttons with UiButton
- `cd231faa` feat(panels): build the rail panels on one UiPanel
- `a3fc475c` feat(cockpit): render the Contact and briefing cards' collapse from the store
- `95523e09` feat(panels): render each panel's state classes from the store
- `dd3a2c87` feat(panels): render collapse, dock and pin buttons from the store
- `ec4c55e7` feat(scenes): render the Scene panel's controls from the store
- `0adcd611` feat(first-run): render the mission launcher from a store
- `c03b4a76` feat(hud): render the Intel HUD from a store
- `b96cc37a` feat(awareness): render the Global Context compass from a store
- `b22e138c` feat(world-overlay): render the visible map target list from a store
- `662f51fd` feat(annotations): render the screen-space annotation board from a store
- `265aa605` feat(celestial-ring): render the full-globe ring from a store
- `fd0d51c4` feat(bhote-koshi): render the reconstruction panel from a store
- `9ea6d7e8` feat(launches): render the replay vehicle overlay from a store
- `e0bfa471` feat(wind): render the inspection marker from a store
- `0926cbc1` feat(voice): render the pointer reticle beside the voice control
- `f9bf782b` feat(ui): render the FPS readout in the title bar from the status store
- `e0abf743` feat(scenes): render the data-pack attribution cards from a store
- `59e3aaa2` feat(scenes): render the Scene actions panel from a store
- `6398103b` feat(ui): render the ORBIT indicator from the location tray
- `f846aaed` feat(ui): render the page toast from the status store
- `3c391482` feat(ui): render the status chips and their split-flap labels from a store
- `492b719f` feat(ui): render the imagery split dividers from a store
- `1de4f635` feat(voice): render the voice control from a presenter
- `9d9eb267` feat(ui): render the scene sharing dialogs and bar from a store
- `fe963a12` feat(ui): render Provider Settings from a store
- `6cb01ff9` feat(ui): render the language picker as a Vue component
- `f279200a` feat(ui): show and hide the Cockpit surfaces from a store
- `484243fe` feat(ui): give every panel one scrollbar, select and slider skin
- `1072df32` feat(ui): render the Radio directory tuner from a store
- `b6d565a8` feat(ui): render the Cockpit utility launchers and compact Radio controls from a store
- `58504e37` feat(ui): render the Cockpit signal rows from a store, keeping focus
- `a2bca0fb` feat(ui): render the Cockpit instruments, route and vision selector from a store
- `ffe14e50` feat(ui): render the Cockpit Contact card from a store
- `82bbf16a` feat(ui): render the Cockpit briefing card from a store
- `d134aefd` feat(ui): render the phone tab bar and sheet backdrop from a store
- `5f8f9bb9` feat(ui): render the location tray's pills, mini status and search error from a store
- `49668778` feat(ui): render the map source chips and status badge from the store
- `decac29f` feat(ui): render the active style in the dock and the ACTIVE STYLE corner from the store
- `66a60ff6` feat(ui): render the Space Missions roster and selected mission from the launches layer's published view
- `1e4df63e` feat(ui): render the Contacts panel from the awareness layer's published view
- `749bfd5c` feat(ui): render the Context mode switch from a store
- `b6c7c130` feat(ui): render the local RTL-SDR card from the store
- `ccb7edd0` feat(ui): render the Radio panel's directory, station card and transport from a store
- `a068a45a` feat(ui): render the Display panel's imported file list from the store
- `b870df41` feat(ui): render the Display panel's Draw controls from the store
- `bca7495c` feat(ui): render the generated style parameter rows through Vue
- `926253e8` feat(ui): render the Display panel's 3D aircraft group from the store
- `1139d364` feat(ui): render the Display panel's Scope and Celestial controls from the store
- `3aa5a3e5` feat(ui): render the Display panel's HUD and Sonar controls from the store
- `c99c0e80` feat(ui): render the Display panel's detection controls from the store
- `343bdebe` feat(ui): render the Display panel's bloom and sharpen from a store
- `d63f4d69` feat(ui): render the data layer rows through Vue from presented row state
- `ce343c1c` feat(ui): render the CCTV camera picker from the store
- `eef3dec7` feat(ui): render the CCTV frame preview, source badge and summary from the store
- `6c7035f6` feat(ui): render the CCTV calibration readout and its pose editor from the store
- `5b8cb40f` feat(ui): render the CCTV panel's buttons, CAL chip and meta line from a store
- `e6aee52e` feat(ui): render the Street Level panel from a store
- `e949584c` feat(ui): render the Recent imagery readout as components
- `a3183762` feat(ui): render the Weather readout as one component
- `ce6040bd` feat(ui): render the rail timeline as a component behind its builder
- `dcecf5c3` feat(ui): render rail cards and card blocks as components behind their builders
- `d9fdcfc6` feat(ui): render the Scene panel's shot list and scene options as components
- `6802c9c8` feat(ui): render every application template except the loading screen as a Vue view
- `9d249451` feat(ui): render application templates as Vue views mounted before wiring
- `3d5d3ef0` feat(ui): add a desktop panel rail to each sidebar
- `2035c767` feat(ui): keep one side panel open per desktop sidebar in every HUD layout
- `7307c11c` feat(ui): add the Vue component kit with UiRail, UiTooltip and UiIcon
- `d4434aa6` feat(outlines): restore voice outlines without public Overpass
- `14d7ddf0` feat(radio): add configurable priority-country coverage
- `05243547` feat(cctv): add Houston TranStar camera pack
- `ffb33247` feat(layers): add FAA drone restrictions airspace layer
- `b1139040` feat(cctv): add the Autostrada del Brennero (A22) motorway webcams
- `b234d7b4` feat(voice): add reusable geometry actions
- `9559e7a2` feat(outlines): voice outlines without Overpass — bundled US places and neighborhoods, guarded Nominatim, OpenFreeMap streets and buildings

### fix

- `6ce9498d` fix(voice): move focus with the voice panel that chat asks for
- `eed61627` fix(voice): follow a new chat request once the log is full
- `51b56181` fix(voice): say the attachment limit is 10 KB in total
- `829db19f` fix(voice): keep the voice preferences in reach from chat Settings
- `4f4af9c4` fix(voice): show the voice panel that typed chat asks for
- `8cd0cc82` fix(cctv): read TranStar dir as the camera's side of the road, at low confidence
- `266825ed` fix(drone-airspace): show FAA times-of-use line breaks as separators
- `585392cb` fix(drone-airspace): refuse cross-site requests to the FAA proxy
- `ca17412c` fix(drone-airspace): redraw a zone when only its boundary changes
- `8e63420f` fix(drone-airspace): show stale FAA snapshots as stale and cap them at a day
- `6bdedd85` fix(drone-airspace): refuse empty or incompletely paged FAA snapshots
- `39165bb1` fix(voice): offer typed chat the same Overpass tools as voice
- `02a67394` fix(awareness): follow a gesture to its last contact, and drop it on blur
- `de634952` fix(awareness): keep a long drag or touch counting as camera input
- `56a7cacb` fix(awareness): ignore canvas input while the cockpit owns the camera
- `fe3d17df` fix(awareness): give the pulse material a named type so Cesium caches it once
- `39a697aa` fix(awareness): keep the range ring a full circle at the poles
- `6b926025` fix(osm): key place-search clients by IPv6 /64
- `cc3d61a9` fix(camera): keep the zoom ceiling fixed while tracking a target
- `c09de47d` fix(voice): mark a stopped reply's running action as cancelled
- `a851199f` fix(awareness): rest the range pulses unless the user moves the camera
- `16b383ab` fix(area): detach a lookup's abort listener once it settles
- `3d2896cf` fix(osm): default an absent /api/osm/features limit to 500
- `68667e2e` fix(area): accept "State of Texas" and "USA" as the units they name
- `b817d580` fix(camera): let a two-finger tilt win over finger-spacing drift
- `e4b39331` fix(camera): read zoom input at the ceiling when the scene is idle
- `08ff7f3e` fix(camera): let a camera above the zoom ceiling zoom in without a jump
- `540629a0` fix(osm): keep a capped place list incomplete in analyst follow-ups
- `4efba8cc` fix(osm): end the server's place search before the voice answer gives up
- `0a8d8241` fix(voice): keep a stopped round's actions and follow-up memory
- `ceb3fe1b` fix(tooling): restore 97 format-scope entries dropped by a merge
- `582bfce6` fix(osm): gate place search like /api/overpass after #1308
- `da8b0dd8` fix(voice): address review of typed AI chat
- `a0924c00` fix: resolve review findings and refresh PR #1518 against main
- `686bc4fd` fix(awareness): draw the 250 km range ring as an unpickable primitive
- `94e4c217` fix(radio): canonicalize priority country aliases before querying
- `0f56b314` fix(awareness): stop the subject echoing itself and cover the echo wiring
- `a2365043` fix: respect camera ownership and finish outward zoom framing
- `e4b43556` fix(voice): keep draw=true in the AREAS rule
- `013cfdf9` fix(awareness): keep range pulses out of picking and in the style palette
- `40d88395` fix(voice): localize the area, imagery and OSM cards and tidy OSM Places
- `20737338` fix(voice): resolve areas per view, without accents and per natural place
- `fb74354d` fix(osm): gate place search cross-site and share its slots fairly
- `e6a6ba01` fix: keep the globe on screen when zooming out from a tilted view
- `0c025987` fix(awareness): bound the range ring pulses so a parked view goes quiet
- `03e9db07` fix(voice): skip the outline lookup for a sized area around a landmark
- `670e952c` fix(voice): name the outline source that answered
- `552f3de3` fix(voice): resolve area names to the place they name
- `dfdbb134` fix(osm): key cached place searches to the Overpass instance that answered
- `474cce51` fix(voice): keep the area in follow-ups on OSM places
- `451be8e3` fix(voice): treat a Zone as retired only in Nepal
- `4edaf245` fix(voice): keep say lines and retry advice in cancelled and failed replies
- `342d9605` fix(traffic): retain line identity across clipping
- `2a629f09` fix(awareness): make the 250 km range ring readable on any ground
- `2a13a06d` fix(voice): bound OpenStreetMap text before it reaches voice results
- `645e13ae` fix(hud): catch the UNAVAILABLE word flush against Han and keep multi-word names whole
- `818d2c82` fix(hud): keep localized summary words whole and drop padding
- `0d3c1ef1` fix(hud): ask again in the new language after an in-place switch
- `9caa0947` fix(traffic): keep a TomTom side from pairing with its own pieces
- `7a39d2d2` fix(traffic): give paired TomTom sides of one street a two-way share of dots
- `c1dd9246` fix(ui): keep the removed Display and layout exports as deprecated shims
- `a767b844` fix(ui): give the Cyber stacks the panel rail clearance
- `dc9d2007` fix(ui): keep the voice highlight on layer rows
- `231ac4b6` fix(ui): return Escape focus to the rail item and read rail direction from the panel
- `54b8060f` fix(ui): keep the scene select on the published scene after a local pick
- `5707a8a1` fix(ui): inset the side panels so their rails clear the HUD edge readout
- `eed76575` fix(ui): let revealed panels own their side and keep Cockpit's left strip
- `dbfbfcce` fix(hud): ask the model only with a place label, catch flush English echoes
- `d6c60f94` fix(cctv): pin A22 frame redirects to WebCamImg/ and refresh on the highway cadence
- `df019641` fix(firms): keep the IPv4 retry from crashing the server; guard the call sites
- `7713fb8a` fix(hud): keep English out of localized summaries, cap ja/zh by characters only
- `7b223d7d` fix(hud): state word first, layer names last; CJK cap by locale
- `f967218a` fix(hud): lead with the state tag, keep feedState in get_hud_caption
- `563df3ba` fix(hud): AI summary in the UI language, canonical feed state, partial aggregation
- `45ae1095` fix(voice): leave aliases a layer id already spells out of the alias hint
- `da2a3c33` fix(sky): read the Milky Way faces by file path in the paint-out test
- `2a335a8f` fix(deps): pin Node 24.22.1 for the October 21, 2026 security release
- `d8358048` fix(dock): show only icons on the narrow dock wings so labels stop covering the voice control
- `19b4a7a7` fix(terrain): keep known heights when a terrain request fails
- `e6d2babe` fix(vessels): pin the idle-render contract and move the entry to a fragment
- `3b572992` fix(director): keep rejected loads from cancelling LOAD; roll back seek only on refusal
- `8cedd159` fix(layers): translate every route proxy refusal and clear stale receiver errorText
- `69c5b325` fix(traffic): date the STALE row by the oldest cached tile; add zh-Hant string
- `7788168d` fix(geocode): prefer the settlement when a POI also fits the region
- `c1820aea` fix(terrain): end retries early on a long Retry-After; cover the 429 pause
- `ac0e124a` fix(flights): read a 359.6° track as 0° in the voice context, not 360°
- `46b3864d` fix(satellites): stop matching a mission to a namesake from another year
- `c6f437ed` fix(traffic): stop a few matched roads reading as "no matches"
- `e4a96437` fix(annotations): label a 996 m line or route as 1.0 km, not 1000 m
- `d1bbfdbc` fix(draw): show a 9,999.6 m² area as 1.0 ha, not 10000 m²
- `c7377362` fix(local-adsb): show a decoder feed's GNSS-sourced vertical rate
- `a2c81328` fix(missions): keep the replay countdown real-time when the speed changes
- `6364817b` fix(directions): show a 9.96 km route as 10 km, not 10.0 km
- `065d7f4f` fix(alpr): show a 359.6° camera bearing as 0°, not 360°
- `182e6ced` fix(tools): list a split submarine cable once in find_submarine_cables
- `f73cd593` fix(missions): run the full T-10 replay countdown after the tile hold
- `e244703f` fix(bikeshare): re-derive a station's missing capacity on every poll
- `812cdf6b` fix(transit): show a reported 359.6° bearing as hdg 0°, not hdg 360°
- `940050d4` fix(cctv): show a camera facing 359.6° as HDG 0°, not HDG 360°
- `accb8983` fix(security): add cross-site gate to military-installations proxy
- `4f7b1bc0` fix(military): read a GNSS-sourced vertical rate when no baro rate is sent
- `83c4388e` fix(awareness): show a 999.6 m contact marker as 1.0 km, not 1000 m
- `ea1b0d8d` fix(voice): leave out an unreported altitude instead of saying 0 feet
- `d58199a2` fix(vessels): show a 359.7° course as 0°, not 360°
- `60dad0c3` fix(military): don't treat adsb.lol's position-less rows as a partial snapshot
- `d0269523` fix(track): name a measured angle violation in the harness log; docs: nginx Host $http_host keeps the port the Origin check compares
- `01c764d4` fix(track): read a late arrival frame before timing it out, so a measured wrong angle is never retried away
- `8f16d10f` fix(overpass): keep proxied traffic out of the direct-loopback admission reserve; keep a measured arrival-angle failure through a reveal timeout
- `4c1ebfb8` fix(traffic): pass fetchFlowDetail through the layer's source slot
- `2c16dd66` fix(geocode): match the nearby whole-name fallback exactly
- `7981a179` fix(traffic): the traffic layer reads STALE, not LIVE, on cached flow tiles
- `25973ade` fix(perimeters): report a stale WFIGS snapshot as stale, and stop serving it after a day
- `923211c2` fix(terrain): key the 429 pause on status, never shorten it, and document it
- `91769d74` fix(geocode): keep a nearby whole-name match as the last choice, and document the region rule
- `7775f600` fix(geocode): a region match takes the place itself, not a name starting with it
- `d7986309` fix(terrain): pause upstream calls after a 429
- `1a61d02b` fix(geocode): a 'place, region' query lands in the region, not on a namesake
- `458def08` fix(director): cover queued and uncertain layer states on same-shot seeks
- `b900fb84` fix(director): reconcile only stale layers on same-shot seeks
- `1644acd2` fix(director): restore layer visibility on same-shot seeks
- `55f979c1` fix(overpass): keyless gate, loopback admission headroom and per-phase arrival budgets
- `76199c07` fix(director): keep a falsy phase error over a release failure
- `cbfcaff8` fix(radio): isolate country coverage from catalog health
- `abf2ce1c` fix: guard scene director callbacks
- `d16620a2` fix: guard scene director callbacks
- `01a6734a` fix(cctv): make the Houston TranStar pack opt-in
- `e82f6d5c` fix(awareness): keep cohort reasons English in data
- `3d64a54a` fix(layers): keep the Local ADS-B receiver error in English
- `4d2a71c1` fix(layers): report Directions errors as English data
- `8e68a29c` fix(cables): preserve feature ownership across multipart geometry
- `166aef58` fix(firms): retry over IPv4 when every address fails to connect
- `177b5951` fix(outlines): harden shared cache and provider lifecycle

### perf

- `3c6c342b` perf(awareness): skip echo work for the whole frame while pulses rest
- `8366803c` perf(analyst): yield area scans on a time budget
- `95267196` perf(layers): pause polled refreshes while the tab is hidden
- `367827e7` perf(vessels): let the scene idle with AIS vessels enabled

### refactor

- `03c168d7` refactor(hud): share the warning line and trim the summary helpers
- `9ed90985` refactor(panels): read panel state from the panel chrome store
- `f269f5be` refactor(cockpit): share one header frame between the Cockpit cards
- `0b8cb4f3` refactor(ui): remove the map stack chip DOM builders
- `2ffd7a4a` refactor(ui): remove the action button and status badge builders
- `5bf797ef` refactor(build): place the views in the page instead of expanding templates
- `f6244e8f` refactor(perimeters): share getSnapshotDetail without this

### docs

- `f120989a` docs(cctv): say the Houston pack needs TxDOT's written permission to enable
- `add905e6` docs(drone-airspace): correct the share token, voice support and coverage
- `daba7f93` docs(awareness): state the range ring's measured ~50 m accuracy
- `895ef536` docs: changelog fragment for #1522
- `682427ef` docs(changelog): move the voice geometry entries to a changelog.d fragment
- `20770e52` docs(changelog): add the range ring sonar pulses fragment for #1519
- `8a50705e` docs(changelog): add the range ring visibility fragment for #1518
- `ab869138` docs(hud): describe the character-only summary cap and trim comments
- `ffd47a36` docs(changelog): credit the voice geometry entries to their commit author
- `57da1090` docs: shorten Codespaces restrictions
- `c6de4594` docs: clarify Codespaces feature restrictions
- `154f8d20` docs(changelog): add #1507 fragment
- `5582ff28` docs: describe the component kit on its own terms
- `859ceac8` docs: name the Vue and Pinia changelog entry after its pull request
- `2dda92c9` docs: record that a map source's unavailableReason may be a function
- `22d4cf8e` docs: move the branch's changelog entries into a changelog.d fragment
- `19ca67a6` docs: require Vue views, Pinia stores and the kit for new UI
- `1cd4dde2` docs(changelog): credit #1495 in the fragment
- `6d6df9d8` docs: plan the Vue migration and the panel rail
- `328894d5` docs(changelog): state the voice hint saving without main's size
- `f976ecf9` docs(changelog): add the voice alias hint entry
- `17d0877a` docs(changelog): add the #1458 fragment
- `ce10a46b` docs(changelog): add the dock icon-only wings entry
- `d0f6f5c0` docs(changelog): add the terrain partial-heights entry
- `bf5cbe74` docs(changelog): add #1454 fragment
- `a22f67ab` docs(changelog): add #1453 fragment
- `197f24d8` docs(changelog): add #1452 fragment
- `420d64ce` docs(changelog): add #1451 fragment
- `50e06181` docs(changelog): add #1450 fragment
- `0e0b82f5` docs(changelog): add #1449 fragment
- `58e9f5ab` docs(changelog): add #1448 fragment
- `f892eaa1` docs(changelog): add #1447 fragment
- `76a3d47e` docs(changelog): add #1446 fragment
- `81cf7915` docs(changelog): add #1445 fragment
- `5d2f6a3c` docs(changelog): add #1444 fragment
- `df71c37d` docs(changelog): add #1443 fragment
- `22b4169a` docs(changelog): add #1442 fragment
- `fdcbcdaa` docs(changelog): add #1441 fragment
- `33985138` docs(i18n): Arabic language notes and right-to-left guidance
- `ffbb0f9d` docs(changelog): add #1436 fragment
- `dc56ada3` docs(changelog): add #1435 fragment
- `5d9264e6` docs(changelog): add #1434 fragment
- `7a1a9cc7` docs(changelog): add #1433 fragment
- `003a6226` docs(changelog): add #1432 fragment
- `5654be50` docs: point Traditional Chinese changelog to replacement PR
- `ae4b3822` docs(changelog): note #1405
- `f3faf373` docs(changelog): note #1404
- `5ef78b97` docs(changelog): note #1401
- `d1bdae20` docs(changelog): note #1402
- `8553b3d5` docs: number changelog fragment for PR 1374
- `ddae593b` docs: credit Traditional Chinese translation sources
- `daedd76a` docs(changelog): fragment for #1308
- `6a537443` docs(current-state): move the #1014 note into its topical section
- `295e164f` docs(readme): say Codespaces moves the server, not the rendering
- `38d16f0a` docs(sdr): record the message / errorText split for receiver errors
- `c0356341` docs(changelog): add the #1209 entry
- `d2de6258` docs: document director playback error handling
- `a856d54b` docs: add cloud setup path via GitHub Codespaces

### test

- `66fb4b6a` test(voice): pin the deadline each chat map action gets
- `c66f8f03` test(cctv): make the oversized Houston catalog fixture valid JSON
- `329ef7e0` test(drone-airspace): check the share token in CURRENT-STATE, not the changelog fragment
- `f6759384` test(voice): record the measured prompt size, 55,210
- `9e378671` test(camera): pin that application controls install the zoom-out guard
- `34647758` test(osm): cover the place-search client and the follow-up handoff
- `0c89a87d` test(voice): cover chat history Down and draft restore
- `98173afd` test(launches): stub the replay panel the speed control now publishes to
- `e40bff37` test(traffic): keep the timing test's Vite cache out of the package tree
- `0e170e05` test(vessels): read the north-rounding HUD heading from the published readout
- `af79691a` test(cctv): check the north-rounding meta line through presentCctvPanel
- `cb6fd756` test(draw): pin the shoelace area in the km² and ha rounding cases
- `9eb969c6` test: format the draw tool test
- `3a2acf9b` test: compare DOM nodes by identity, never through assert.equal
- `b7e7058a` test: compile option-API components and report template errors in the Vue test loader
- `71574179` test(qa): skip the seek visibility check outside a Vite dev server
- `d57bc0af` test(locator): give the Stop test double the seek-generation helper
- `811eb783` test(director): cover observer failures in session activate and clear
- `f7a7a76f` test(embed): pin the panel-aware visibility wiring in data setup
- `3321affa` test(voice): check a sea-level altitude is still spoken
- `5410c973` test(terrain): fail the first 429 test instead of hanging if its request never settles
- `3ac98688` test(terrain): bound the 429 pause test's settle loop
- `58a41759` test: resolve sky texture file URLs on Windows
- `e3c4e88d` test(track): freshen rotation passes before the arrival probe and retry an inconclusive timeout
- `a275c2c6` test: pin voice schema and README layer count for drone airspace

### chore

- `7a421c35` chore: drop the duplicate format-scope entry from the main merge
- `bf2c96db` chore: leave the #1264 changelog fragment as merged
- `01979bba` chore(stack): refresh voice core and outlines parents

### other

- `6cede0f2` Merge origin/main (acc9531b) into the range ring visibility branch
- `fa8db45d` Merge commit '2ebde97fb3af19402eab83fca2bfbec9ddfd166a' into easy-wins-20261103-pr1518
- `a6d20120` Merge upstream main into PR #1435 for integration review
- `aff540ad` Merge upstream main into PR #1206 for integration review
- `315c561a` Restore main's catalog strings and re-pin the voice schema after the main merges
- `81ffa5b6` Suspend the tuner noise context once a pending resume settles
- `ecaddd83` Merge feat/voice-geometry onto main
- `317de931` Say which HUD readouts are real camera values and which are styling
- `b9f3dd64` merge feat/voice-outlines 3ac3499e into the review fixes
- `3ac3499e` merge main 43a67f9 into feat/voice-outlines
- `c35eba17` Merge main into prereq-10-osm-overlays
- `64c9f4cf` let building words pass only on single-structure results
- `c059e12a` merge main 17daf897 into feat/voice-outlines
- `0712db98` address the final review of the voice outline fixes
- `f38961ef` Merge main into the Utilities panel
- `672a1452` Keep Contact folded until both Cockpit left panels close, and keep focus in a renamed row
- `a61d0f4c` tighten the remaining voice outline review items
- `345d5db5` Point the Draw and layer panel gates at Utilities and at what is drawn
- `e35483d3` Give Utilities the room Data Layers gets in Cockpit
- `46b23ccc` Let voice open the Utilities panel
- `38eb98b8` Take a hidden shape off the globe whole, and keep every drawn shape
- `4ebb287d` Merge main into the Utilities panel, rebuilt on the Vue panel rail
- `a38a065c` keep bent streets, enclosed landmarks and same-name outlines honest
- `fc7ff105` Split Open Map Overlays into Sea Marks and Ski Pistes layers
- `c489e657` Keep one OpenStreetMap copyright link in the data credits
- `ce1ad3b9` Merge main into prereq-10-osm-overlays and port Open Map Overlays
- `d646fdbe` Pin Node 24.22.2, the current 24 LTS patch, keeping 24.22.1 as the security floor
- `c572a28e` Mend the test prerequisites, document local CCTV packs without the dead demo feed, and credit the author
- `799273b3` Test the installations gate with the Overpass proxy tests, drop the stray PR body, and correct the fragment
- `e9c6f254` Drop the gap beside the icon-only dock wings, point the state doc at the Vue dock, and credit the author
- `9fecc9c4` Say the alias hint filters only the first two aliases, and drop an id the filter now covers
- `16756bb7` Align the doctor, state doc and bug template with the 24.22.1 pin, and credit the author
- `8a23328e` Describe multipart cable ownership by behaviour and credit the author's handle
- `91269cda` Keep the Codespaces port private, say Provider Settings stays shut there, and credit the path
- `cfc83a60` Release the tuner noise graph after a silent dial release
- `857b007f` Keep the Radio tuning dial silent unless a stream is playing
- `a2be947a` Merge origin/main into fix/hal-722-radio-next-no-autoplay
- `d479c1c6` Read an ADS-B vertical rate from one shared field reader
- `411cfd85` Record the shared launch-year parser in the state doc and fragment
- `4779432e` Read a satellite's launch year from one TLE parser
- `d1420516` Format every metre/kilometre distance through one shared helper
- `d9a46065` merge main 0c28dc7 into feat/voice-outlines
- `0e90a03d` Round every heading readout through one shared helper
- `c5aa0d28` merge main 07094d9 into feat/voice-outlines
- `bc5d038a` Merge Core main into german/hal-644-ar: Arabic on the Vue UI
- `5605fdc6` Merge Core main into sameh/core-vue
- `183e651c` Show Cyber's edge lines beside open panels, on both sides
- `06994e0d` Keep the panel rails still when a tall panel opens
- `b20c80e5` Switch language in place, without a reload
- `70494698` Keep a refreshed weather credit through frame installs and host switches
- `903f5930` Add the changelog entry for weather product display metadata
- `039b0828` Let a weather source describe its own products
- `20ad658f` Resolve localhost to both loopbacks in the real connect-failure test
- `691f2738` Add the changelog entry for the GNSS source window
- `e1bbbcec` Let a GNSS integrity source set the layer's evidence window
- `f19da926` Merge upstream main and resolve radio coverage conflicts
- `62a36b96` keep tile outlines honest when the anchor tile fails to load
- `c61ddb38` keep the phone credit line on screen
- `38226ac3` merge main a725178 into feat/voice-outlines
- `3824b4eb` keep cancelled outline and search asks free during the Nominatim probe
- `f32ab544` skip Nominatim lookups when the server has none configured
- `24228b14` merge main bb6f501 into feat/voice-outlines
- `e6ad7fe3` tighten remaining voice outline review items
- `a71443a0` drop the unused Nominatim outline center
- `ab1239d3` Cap rail title size and keep compact type to launchers
- `3def533d` merge main a16eb07 into feat/voice-outlines
- `bdbbc3d7` Keep Draw rows in place across board changes, and frame lines across the antimeridian
- `94470ff0` Translate the Utilities panel and Draw list strings in de, fr, it, ja, pt and uk
- `2e82425d` address review findings on voice outlines
- `38302a27` Merge upstream/main into feat/cctv-a22-autobrennero
- `bae3433b` Merge upstream/main into fix/firms-ipv4-fallback
- `5a1cfa68` merge main 423ca3ca into feat/voice-outlines
- `578ebdc0` merge main f13c60c into feat/voice-outlines
- `44f9138d` Keep panel titles inside their cards and scope the hover
- `5ed86200` Bring back the tuner-release and connecting-label Radio fixes
- `a55450e2` Trim the Radio Next/Previous change to the HAL-722 scope
- `fa840ae3` Translate the Radio privacy note into the new locales
- `4dd5a313` Keep Radio playback state consistent after a silent Next
- `2640f637` Add the changelog entry for the CCTV view thinning
- `93942d0d` Show only the CCTV cameras in view, thinned to one per ground cell when zoomed out
- `a4820315` Translate Authoring for the six new languages and fit long words
- `5a80facf` Address review: playable PLAY/NEXT, visible rename editor, accurate copy
- `16c88880` Prune the removed Radio strings from the catalogs main added
- `9520238b` Move the changelog entry to changelog.d and clear review leftovers
- `a8127c96` Drop the Operator string from the Japanese catalog
- `151e7ad5` Drop the Operator string from the German and French catalogs
- `ce47af6f` Restore the Snow retirement in tests the main merge overwrote
- `aa0f6d4e` Remove the HUD top bar that no layout shows
- `607cd770` Drop the Operator string from the Italian, Portuguese and Ukrainian catalogs
- `32125384` Drop Snow from the new catalogs and migrate saved Snow shots
- `6f93c21a` Describe the Draw shape list in the Utilities panel changelog entry
- `b775bfed` Add the changelog entry
- `1ef9be22` Keep Radio Next and Previous from starting playback before Play
- `97b7307b` Fix the format gate and the Cyber Context styling, and pin the redesign
- `95ed686d` List drawn shapes under Draw, with icon shapes and colour swatches
- `8de75b17` Keep two shot rows visible in Authoring on shorter windows
- `8543b7be` Keep Directions reachable and tested in the Utilities panel
- `4192a6f8` Keep Authoring within its stack and theme, and cover its wiring
- `3b6111be` Open views naming the retired Snow style on Normal
- `45229200` Add the changelog fragment for the Authoring panel
- `2b1129c1` Rename the Scenes panel to Authoring and lay it out in steps
- `e12614a1` Pin the retired Operator code and test the live HUD fallback
- `66e19f0c` Drop the Radio icon from Context and make the panel easier to read
- `d730b0ce` Add the changelog fragment for the Utilities panel
- `2b5770c6` Add the changelog entry for the Snow removal
- `39a60b40` Remove the Snow visual preset
- `08dd88b2` Gather Directions, Draw and Import in a Utilities panel
- `e693e665` Add the changelog entry for removing the Operator HUD layout
- `8b2c6993` Remove the Operator HUD layout
- `361f7de3` Add the changelog entry for the panel chrome change
- `d2647f35` Give the side panels one title style, hover and toggle inset
- `391dba74` Add the changelog entry
- `f69e9bba` Update Vite and Puppeteer, and remove the unused screenshot helper
- `d1e0ff4e` Name the HUD lookups changelog entry after its pull request
- `c1f60cb7` Cut the Google requests the HUD summary makes on its own
- `4c2159a7` Merge upstream/main into fix/drone-airspace
- `ba9db7fc` Merge origin/main and sync Traditional Chinese catalog
- `48bfaa78` Merge main; give the HUD visibility test's camera a moveStart event
- `fdda5b7a` Abort superseded same-shot seeks and roll back partial layer restores
- `1161899a` Merge main; keep inline panels polling while their host reports them hidden
- `4c0a8e37` Merge upstream main and migrate cable changelog to fragment
- `f6fa5bf1` Merge upstream/main into docs/add-codespaces-deployment
- `d64cd1dc` Merge upstream/main into fix/scene-director-callback-errors
- `3109ddab` add trailing newline to playback test
- `41b24753` Merge main into feat/voice-outlines
- `feba5af0` Add OpenSeaMap / OpenSnowMap overlay layers (#10)
- `e3772f80` Clarify test:track command usage in CONTRIBUTING.md
- `d04939b8` fix:docs

### merges

273 merge commits (pull request merges and branch syncs, not listed).

### build

- `7d236a11` build: cache compiled components and load them on the test thread
- `c13c487d` build: add Vue and Pinia to the browser build and unit tests

### changelog

- `c6fff6e7` changelog: note the rail pills
- `edf8c092` changelog: note the component cache
- `54750a01` changelog: HUD summary language (#1488)
- `ef5b44f2` changelog: Arabic (#1479)
- `29692ac7` changelog: Japanese (#1478)
- `6ab9432a` changelog: German (#1477)
- `e44d15cd` changelog: French (#1476)
- `01a097ca` changelog: Brazilian Portuguese (#1475)
- `cf1ef368` changelog: Italian (#1473)
- `1abe8cbb` changelog: Ukrainian (#1470)

### i18n

- `ba0dd1da` i18n(voice): use a label for the imagery area line
- `acbba74d` i18n(voice): tighten the geometry translations after a second review
- `1f9a453b` i18n(ar): own the Arabic catalog in the application package; mirror select chevrons
- `ba20bc13` i18n: translate the application views with t() as they render
- `2c72a038` i18n: keep the page's locale in a vue-i18n instance
- `62bf27ca` i18n: landing labels in de, fr, it, ja, pt and uk; ar cyclone errors; prune FIRES and Snow
- `32d6ce4e` i18n(ja): translate strings new in main, drop Snow
- `56ca3402` i18n: keep Upper Trishuli as a place name; drop duplicate cyclone keys
- `aaadf708` i18n: Upper Trishuli in fr, it, pt and uk; drop Snow from de
- `48a2cc06` i18n(fr): drop the Snow strings removed in main
- `f9af9e75` i18n(fr): translate strings new in main
- `b0f0837c` i18n(it, uk): translate the cyclone source errors
- `04481ef2` i18n(ar): address code review findings
- `f8e96e14` i18n(it): address code review findings
- `0e45bcdf` i18n(de): address code review findings
- `eab345a4` i18n(pt): address code review findings
- `d034e735` i18n(fr): address code review findings
- `a1d98479` i18n(ja): address code review findings
- `d383f25b` i18n(it): translate strings new in main
- `6c524b22` i18n(pt): translate strings new in main
- `8c291d8a` i18n(ar): translate strings new in main
- `eab96327` i18n(ja): translate strings new in main
- `eb76d526` i18n(uk): translate strings new in main
- `ed26fa12` i18n(fr): translate strings new in main
- `a0c8b6f8` i18n(de): translate strings new in main
- `df8dd2ad` i18n(ar): apply review round 5
- `8da577da` i18n(ja): apply review round 4
- `0511153b` i18n(ar): apply review round 4
- `d01be22b` i18n(de): apply review round 5
- `a312414d` i18n(fr): apply review round 5
- `d243177d` i18n(uk): apply review round 4
- `a96ad30c` i18n(pt): apply review round 4
- `42345209` i18n(de): apply review round 4
- `3d32a0c4` i18n(fr): apply review round 4
- `4c80c38e` i18n(it): apply review round 4
- `df866f33` i18n(ar): apply review round 3
- `226600a6` i18n(uk): apply review round 3
- `85405358` i18n(ar): apply review round 2
- `7e55ee45` i18n(fr): apply review round 3
- `6b3876b1` i18n(ja): apply review round 3
- `bceeb378` i18n(de): apply review round 3
- `40485359` i18n(pt): apply review round 3
- `beacb6d9` i18n(uk): apply review round 2
- `6cf47c6c` i18n(it): apply review round 3
- `cd1f5736` i18n(ja): apply review round 2
- `b521f6a1` i18n(de): apply review round 2
- `858ce827` i18n(pt): apply review round 2
- `e87001d0` i18n(fr): apply review round 2
- `8ca7f52d` i18n(ja): apply review round 1
- `4f44a17b` i18n(ar): apply review round 1
- `b96c1dee` i18n(it): apply review round 2
- `1eb9e06c` i18n(de): apply review round 1
- `3c0c10d3` i18n(pt): apply review round 1
- `7a18e009` i18n(uk): apply review round 1
- `5e47a2af` i18n(it): apply review round 1
- `4adb9113` i18n(fr): apply review round 1
- `cdd90dac` i18n(uk): fixes from the screenshot review
- `91f1f80e` i18n(ar): Arabic face for the Global Context lines
- `9bf8395c` i18n(ar): wording fixes from the screenshot review
- `d33f914a` i18n(ar): reset letter-spacing on every Arabic container
- `0d28150e` i18n(de): fixes from the screenshot review
- `d6ecaca9` i18n(ja): fit labels found in the screenshot review
- `56a36df0` i18n(pt): fit cockpit labels found in the screenshot review
- `d95bffb5` i18n(fr): fit French labels found in the screenshot review
- `9de91068` i18n(it): shorten labels that wrapped or clipped on screen
- `4c3e3662` i18n(ar): keep values whole in right-to-left text
- `06370d86` i18n(ar): mirror the layout right to left
- `9f71a62d` i18n(fr): ship French in the language picker
- `402f5695` i18n(fr): translate the rest of the French catalog
- `ed402014` i18n(ja): ship Japanese
- `7ad073aa` i18n(ja): translate the remaining strings and review #913
- `11469462` i18n(uk): complete and ship Ukrainian
- `0b928b68` i18n(ar): register Arabic as the first right-to-left language
- `94dc2736` i18n(ar): translate the remaining Arabic strings
- `dfa7ac98` i18n(de): complete and ship German
- `8269f0e4` i18n(pt): complete and ship Brazilian Portuguese
- `c4dfee6e` i18n(it): ship Italian
- `2172183d` i18n(it): translate the remaining strings and review #912
- `7d7c535d` i18n(de): German strings from #908
- `6167aae6` i18n(fr): French strings from #907
- `ce17d0ca` i18n(pt): Portuguese strings from #909
- `8785f4c8` i18n(ar): Arabic strings from #915
- `e2acee4b` i18n(uk): Ukrainian strings from #312
- `bdd24798` i18n(ja): Japanese strings from #913
- `978cd72a` i18n(it): Italian strings from #912
- `982edfd5` i18n: use 公布 in zh-Hant to match 發布
- `018b6d3f` i18n: fix zh-Hant characters OpenCC converts wrongly
- `51ee9ae9` i18n: write zh-Hant as zh-CN in Traditional characters
- `8269facb` i18n: address Traditional Chinese translation review
- `8f16cf26` i18n: use zh-Hant for Chinese (Traditional)
- `6b3e8bad` i18n: add Traditional Chinese (zh-TW)

### style

- `4f95763a` style: format the new area and place-search tests
- `babd55ea` style(voice): centre main's icon-only dock wings
- `e3054477` style(ja): CJK label rules for Japanese
- `9059cd94` style: format the Overpass admission tests

### diffstat

```
src/voice/pointerReticleView.test.mjs                        |   83 +
 src/voice/providerCommands.js                                |   11 +-
 src/voice/providerCommands.test.mjs                          |  136 +-
 src/voice/realtimeBackend.test.mjs                           |    7 +-
 src/voice/realtimeConnection.js                              |    4 +
 src/voice/realtimeController.js                              |   47 +-
 src/voice/realtimeCost.js                                    |   76 +-
 src/voice/realtimeCostIncompleteNote.i18n.test.mjs           |   13 +-
 src/voice/realtimeCostPanel.test.mjs                         |   98 +-
 src/voice/realtimeCostTierStatus.test.mjs                    |   13 +-
 src/voice/realtimeInput.js                                   |   76 +-
 src/voice/realtimeInputPolicy.js                             |   13 -
 src/voice/realtimeNarration.test.mjs                         |    8 +-
 src/voice/realtimeOwners.test.mjs                            |   45 +-
 src/voice/realtimeProtocol.js                                |   40 +-
 src/voice/realtimeProtocol.test.mjs                          |  108 +
 src/voice/realtimeRadio.js                                   |    2 +-
 src/voice/realtimeRadio.test.mjs                             |   13 +-
 src/voice/realtimeSession.js                                 |   62 +-
 src/voice/realtimeTurns.js                                   |    1 +
 src/voice/realtimeTypedSend.test.mjs                         |   11 +-
 src/voice/referents.js                                       |    6 +-
 src/voice/resultDisplay.js                                   |  270 ++-
 src/voice/session.test.mjs                                   |  152 +-
 src/voice/sessionCommands.js                                 |  240 ++-
 src/voice/speech.js                                          |   83 +-
 src/voice/speech.test.mjs                                    |   88 +
 src/voice/textChat.js                                        |  533 +++++
 src/voice/textChat.test.mjs                                  |  515 +++++
 src/voice/textProtocol.js                                    |  190 ++
 src/voice/voiceCard.js                                       |  153 +-
 src/voice/voiceCard.test.mjs                                 |  204 +-
 src/voice/voiceCardPlanSteps.i18n.test.mjs                   |   63 +
 src/voice/voiceCardPresentation.js                           |    5 +-
 src/voice/voiceControlView.test.mjs                          |  132 ++
 src/voice/voiceMiniPreview.js                                |   70 +
 src/voice/voiceMiniPreview.test.mjs                          |  105 +
 src/voice/voiceWorkflowHarness.mjs                           |  126 +-
 style.css                                                    |    5 +-
 1386 files changed, 134966 insertions(+), 23867 deletions(-)
```

