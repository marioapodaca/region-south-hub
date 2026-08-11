# Region South Visual Style Guide — AI-Ready Specification v1.4

## Purpose
Create visuals that are consistent with the Region South visual system, aligned to LAUSD brand standards, student-centered, data-accurate, and optimized for clear communication.

Priority order:
1. Data accuracy
2. Brand compliance
3. Readability
4. Correct subject identity
5. Student representation
6. Aesthetic polish

If visual styling conflicts with data accuracy, data accuracy wins.

---

## Canonical assets

### Region South logo
https://github.com/marioapodaca/region-south-hub/blob/main/RS-logo.png

Rules:
- Use only the authentic approved asset supplied by the user or explicitly identified in this guide.
- Do not redraw, recolor, distort, rotate, crop, approximate, stylize, reinterpret, reconstruct, or invent it.
- Do not assume a default placement. Place the logo only where the design, an approved template, or the user specifically requires it.
- Do not duplicate the logo in a footer, corner, decorative area, or secondary location unless specifically requested or defined by an approved template.
- If the logo cannot be inserted reliably and exactly, omit it rather than fabricate or approximate it.

### LAUSD seal
https://github.com/marioapodaca/region-south-hub/blob/main/LAUSD_seal.png

Rules:
- Use only the authentic approved asset supplied by the user or explicitly identified in this guide.
- Do not redraw, recolor, distort, rotate, crop, approximate, stylize, reinterpret, reconstruct, or invent it.
- Place it only where specifically requested or defined by an approved template.
- Do not add or duplicate it merely to fill unused space.
- If it cannot be inserted reliably and exactly, omit it rather than fabricate or approximate it.

### LAUSD Brand Guide
https://communications.lausd.org/apps/pages/index.jsp?uREC_ID=4433467&type=d&pREC_ID=2674581


## Logo control and brand placement

### LOGO CONTROL
Use only authentic, approved Region South and LAUSD logo assets supplied by the user or explicitly identified in the Region South Visual Style Guide.

Never create, redraw, approximate, stylize, reinterpret, reconstruct, or invent any Region South, LAUSD, school district, school, program, or organizational logo, seal, badge, crest, emblem, wordmark, or similar brand mark.

Do not add decorative logos, seals, badges, crests, or emblems simply because a layout contains unused space or a footer area.

If an authentic logo asset is not available or cannot be reproduced accurately, omit the logo rather than approximating it.

### BRAND PLACEMENT
Use approved Region South and LAUSD branding only in locations defined by the design or specifically requested by the user.

Do not duplicate branding unnecessarily.

Do not place logos, seals, badges, or emblems in a footer, corner, decorative area, or secondary location unless that placement is specifically requested or defined by an approved template.

### IMAGE-GENERATION RESTRICTION
Treat all logos, seals, badges, crests, emblems, wordmarks, and official marks as protected brand assets, not as decorative graphic elements.

When generating or regenerating a Region South visual, explicitly instruct the image model:

> “Do not invent, approximate, redraw, stylize, or add any logo, seal, badge, crest, emblem, district mark, or organizational mark. Use only authentic approved assets provided for the design. If an approved asset cannot be reproduced exactly, omit it.”

For image-generation workflows, the safest production sequence is:
1. Generate the composition without allowing the image model to invent official marks.
2. Add authentic approved logo assets in a post-production/compositing step when branding is required.
3. Validate every visible official-looking mark before finalizing.

**Core brand rule:** An invented or approximated logo is a brand-compliance failure, even if it looks visually appropriate or resembles an official Region South or LAUSD asset.

---

## Official LAUSD colors

| Name | Hex | Core use / restrictions |
|---|---|---|
| LAUSD Navy | #00237A | Primary institutional blue; Math anchor color |
| LAUSD Bright Blue | #0089FF | Use with navy or white; do not use for text smaller than 17 pt |
| LAUSD Green | #00602D | Science anchor color; use with white; do not use directly on navy; do not use with navy type |
| LAUSD Orange | #FF4D00 | ELA anchor color; do not use for text smaller than 17 pt; do not use with red text |
| LAUSD Gold | #FF9C00 | Can be used with navy type; do not use as text on white; do not use for text smaller than 17 pt |
| LAUSD Red | #FF0000 | Prefer white as primary pairing; use with navy sparingly; do not use for text smaller than 17 pt |

---

## Subject color system

Hard rule:
**Subject determines the color family. Region determines the shade.**

- Math = blue hues
- ELA = orange hues
- Science/CAST = green hues

Do not switch subject color families.

### Locked regional comparison palette

#### Math
- South: #00237A
- East: #0089FF
- North: #001A5A
- West: #6F8FAF

#### ELA
- South: #FF4D00
- East: #FF8A4C
- North: #B93600
- West: #C97A55

#### Science
- South: #00602D
- East: #5CBF82
- North: #003D1D
- West: #70947F

Rules:
- Do not deviate from these colors in regional comparison graphics.
- Use the same region color in every chart within the same visual.
- South receives the strongest visual emphasis, but other regions must remain legible.

---

## Typography

Primary presentation/data typeface: **Poppins**

Recommended hierarchy:
- Major title: Poppins Bold / ExtraBold
- Section heading: Poppins Bold
- Subtitle: Poppins Medium
- Chart title: Poppins SemiBold
- Large metric: Poppins Bold / ExtraBold
- Body: Poppins Regular
- Chart labels: Poppins Medium
- Footer/source: Poppins Regular
- Digital body alternative: Open Sans
- Fallback: Arial

Avoid Thin/ExtraLight in presentation graphics.

---


## Display Mode — Required User Choice

Region South supports two approved display modes:

### Light Mode
Best for:
- printed reports
- dense analytical charts
- detailed regional comparisons
- maximum color contrast
- documents likely to be exported to PDF or printed

Default visual treatment:
- white or soft-white background
- navy primary text
- light chart cards
- subject/regional colors used directly on light plotting areas

### Dark Mode
Best for:
- presentations
- executive dashboards
- hero graphics
- title/section slides
- visuals using student photography
- large-screen display

Default visual treatment:
- Region South navy background
- white primary text
- light-blue secondary text
- dark cards/panels
- detailed plotting areas may still be white/light when needed for contrast or LAUSD color compliance

### Required interaction rule
If the user has not specified a display mode, ask:

**Would you like this graphic in Light Mode or Dark Mode?**

Explain:
- Light Mode works best for print, dense charts, detailed comparisons, and maximum color contrast.
- Dark Mode works best for presentations, executive dashboards, hero graphics, and student photography.
- If unsure, the user may ask for a recommendation.

If the user asks for a recommendation:
1. Recommend Light or Dark based on the content and audience.
2. Explain the reason briefly.
3. Obtain user confirmation before generating the final visual.

Hard rule:
**Do not silently choose Light or Dark Mode when the user has not specified a mode.**

## Layout templates

### RS-01 — Hero Data
Use for SBA trend graphics, CAST, attendance, and single-subject dashboards.

Structure:
PHOTO | PRIMARY DATA | KEY TAKEAWAY

Typical proportions:
- Photo: 20–30%
- Main data: 45–55%
- Key takeaway: 20–25%

### RS-02 — Regional Comparison
Use for East/North/South/West comparisons.

Structure:
P+A | DFP or SP | REGION SOUTH STORY

Rules:
- Region South gets strongest visual emphasis.
- Comparison regions remain visible and fair.
- Use locked regional colors.

### RS-03 — Cohort Analysis
Use for grade-level small multiples and achievement-level movement.

Structure:
MULTIPLE GRADE PANELS
STUDENT IMAGE | KEY TAKEAWAY

Rules:
- Use consistent axes across small multiples when comparison is intended.
- Preserve category order across panels.

---

## Photography

Style:
- Photorealistic
- Authentic
- Student-centered
- Academically engaged
- Optimistic
- Age-appropriate

Rules:
- Students must be actively learning, not decorative props.
- Student age must match the grade span.
- Use realistic demographic diversity across the image set.
- Avoid stereotypes and repetitive demographic compositions.
- Data readability takes precedence over photography.
- Preferred placement: left, lower-left, or lower-third.
- Blend photography into the background; avoid hard rectangular edges.

### ELA
Activities:
- Reading
- Annotating
- Discussing text
- Writing in response to reading

Icon:
- Open book
- LAUSD Orange #FF4D00

### Math
Activities:
- Solving equations
- Calculator use
- Graphing
- Collaborative problem-solving

Icon:
- Calculator
- LAUSD Navy #00237A

### Science / CAST
Activities:
- Conducting an experiment
- Measuring liquids
- Recording observations
- Discussing results

Props:
- Beakers
- Flasks
- Graduated cylinders
- Microscope
- Pipettes
- Lab notebook
- Safety goggles where appropriate

Icon:
- Beaker, flask, or microscope
- LAUSD Green #00602D

---

## Terminology

### P+A
Full name: **Proficient + Advanced**

Source aliases that may appear in uploaded data:
- PoA
- Percent Proficient or Advanced

Display rules:
- Use **Proficient + Advanced** when space permits.
- Use **P+A** when space is constrained.
- Do not display **PoA** in Region South-facing visuals.

### DFP
Full name: **Distance from Proficiency**

Interpretation:
- Higher values indicate stronger performance.
- Values closer to zero are closer to proficiency.
- Positive values are above proficiency.

### SP
Full name: **Science Points**

Use **SP** when space is constrained.

### Required abbreviation definitions
If **P+A**, **DFP**, or **SP** appears anywhere in a visual, its full definition must also appear somewhere in the same visual.

Preferred locations:
1. Under chart title
2. Footer/notes area
3. Methodology/info panel
4. Legend area if already present

Examples:
- P+A = Proficient + Advanced
- DFP = Distance from Proficiency
- SP = Science Points

---


## Subject color precedence for SBA/CAASPP graphics

For SBA/CAASPP academic data graphics, **subject color takes precedence over generic positive/negative bar coloring**.

Hard rules:
- Math chart marks (lines, bars, primary data shapes) use the approved blue family.
- ELA chart marks use the approved orange family.
- Science/CAST chart marks use the approved green family.
- Do not color Math bars green/red merely because the numeric change is positive/negative.
- Do not color ELA bars green/red merely because the numeric change is positive/negative.
- Do not color Science bars blue/orange merely for decoration.

Communicate favorable/unfavorable meaning through:
- bar direction above/below zero
- up/down arrows
- concise text labels
- outline, pattern, saturation, or light/dark variants within the subject family
- limited semantic callouts when needed

Red may still be used sparingly for warnings, declines, embargo notices, or a "largest decline" callout, but it should not replace the subject family as the primary data encoding.

Green may still be used sparingly for favorable callouts in Math/ELA, but it should not replace the subject family as the primary data encoding.

---

## Subject icon validation

The subject icon must match the subject:
- Math: calculator
- ELA: open book
- Science: beaker, flask, or microscope

Do not use an open-book icon on a Math graphic or a calculator icon on an ELA graphic.

---

## Logo validation

Generated, approximate, invented, reconstructed, stylized, or substitute logos are non-compliant.

If an authentic Region South, LAUSD, school, district, program, or organizational asset cannot be placed exactly:
- omit the logo/mark from the generated image;
- reserve clean space only when the design requires later placement;
- add the authentic approved asset in a post-production step when needed.

Never generate substitute text logos or marks such as approximate “LAUSD,” “RSSAS,” altered Region South marks, circular seals, badges, crests, emblems, or other official-looking decorative marks.

Do not add a logo simply because a corner, footer, or empty area appears available.

Do not duplicate branding unless the user specifically requests it or an approved template defines multiple placements.

### Final validation — brand assets
Before finalizing any Region South visual, verify:
- Every visible logo or official mark is an authentic approved asset.
- No logo, seal, badge, crest, emblem, or wordmark was invented by the image generator.
- No unrequested duplicate branding was added.
- No decorative mark could reasonably be mistaken for an official Region South, LAUSD, school, district, or program logo.
- If an authentic asset could not be reproduced accurately, it was omitted rather than approximated.

**An invented or approximated logo is a brand-compliance failure, even if it looks visually appropriate or resembles an official asset.**

---

## Preliminary trend privacy check

For embargoed/restricted values, a generalized trend must not reveal the value through its endpoint.

Do not:
- terminate the arrow at a meaningful y-axis coordinate
- align the arrow with a gridline from which the value can be estimated
- use a precisely scaled arrow length

Preferred treatments:
- directional arrow in a separate "Preliminary Trend" zone
- arrow that indicates only up/down direction without sharing the quantitative axis
- textual "improving trend" / "declining trend" treatment when the chart position could disclose magnitude


## Data visualization rules

### General
- Accurate scale
- Minimal clutter
- Direct labeling where useful
- Fair comparison
- Emphasize Region South without distortion
- Avoid decorative elements that do not support the data story

### P+A
- Higher = stronger performance
- Preferred chart for trends: line chart
- Use percentage formatting consistently
- Describe differences in **percentage points**, not percent change, unless percent change is intentionally calculated

### DFP
- Higher = stronger performance
- Show 0 as Proficiency when relevant
- Keep minus signs visible
- Do not reverse the axis to make improvement look upward artificially
- Preferred benchmark label: **Proficiency**

### SP / CAST
- Scale: 0–100
- Proficiency benchmark: 65
- Benchmark label: **Proficiency**
- Do not call it "Proficiency Floor"

### Data labels
Prefer selective direct labels:
- first point
- final point
- turning point
- historically significant high/low
- values referenced in the takeaway

### Axis integrity
Do not:
- reverse axes merely for appearance
- use inconsistent scales across comparison panels without disclosure
- truncate axes in misleading ways
- distort time spacing when slope interpretation matters

For formal slope analysis, use actual elapsed time.

---

## Growth, trend, and acceleration language

### Improvement
Performance moved in a favorable direction.

### Growth
Improvement observed over multiple periods.

### Average annual change
(final value - starting value) / elapsed years

### Linear trend slope
Regression-based slope using all available observations.

### Acceleration
The rate of improvement itself is increasing.

Do not call ordinary positive growth "acceleration" unless the annual gains themselves are increasing.

Claims such as:
- largest
- strongest
- fastest
- highest
- lowest
- most improved

must include a defined comparison period.

---

## Preliminary and embargoed data

If actual values are restricted:
- Do not show the actual value.
- Use a generalized dotted/dashed direction indicator.
- Label it **Preliminary Trend**.
- Do not place the endpoint precisely enough to infer the restricted value.
- Do not use precise arrow length or position that reveals magnitude.

Preferred language:
**Preliminary results remain embargoed and are shown only as a generalized trend.**

For stronger internal-use treatment:
**PRELIMINARY — INTERNAL USE ONLY**

---

## Reusable components

### RS-C01 — Key Takeaway
Structure:
[icon] KEY TAKEAWAY
Short interpretation paragraph
Optional metric callouts

Max recommended body length: ~70 words.

### RS-C02 — Metric Callout
Examples:
+29.5
DFP points improved

+8.8 pts
P+A gain

### RS-C03 — Measure Definition
Required whenever P+A, DFP, or SP appears.

### RS-C04 — Proficiency Benchmark
Examples:
0 = Proficiency
65 = Proficiency

### RS-C05 — Preliminary Trend
Dotted/dashed line + arrow + Preliminary Trend label.

### RS-C06 — Internal Use Notice
PRELIMINARY — INTERNAL USE ONLY

### RS-C07 — Data Metadata
Source and date information.

### RS-C08 — Data Panel
Rounded dark navy panel with thin light border and generous padding.

### RS-C09 — Region Label
Consistent region naming and locked color.

---

## Metadata behavior

Before finalizing a Region South data graphic:

If **Source** is missing, ask the user:
"What source should be listed? If a source is not pertinent for this graphic, I can omit it."

If **date** is missing, ask the user:
"What download or data-as-of date should be shown? If a date is not pertinent, I can omit it."

If both are missing:
"What source should be listed, and what download/data-as-of date should appear? If either item is not pertinent, I can omit it."

Never invent:
- source
- date
- date meaning

Approved date labels:
- Data as of
- Downloaded
- Results through

Users may explicitly omit either or both items.

---

## Footer standard

Preferred three-zone footer:

LEFT (only when branding is specifically requested or defined by an approved template):
Authentic Region South / LAUSD branding. Do not create or add a decorative substitute mark. If branding is not required, leave this zone unbranded or use approved non-logo content.

CENTER:
Definitions, methodology, preliminary/internal-use note

RIGHT:
Source and date

Example:
P+A = Proficient + Advanced · DFP = Distance from Proficiency
Source: CAASPP
Data as of August 8, 2026

---

## AI self-check before generating

### Brand
- Correct subject family?
- Correct region colors?
- Is every visible official mark an authentic approved asset?
- Did the image generator invent, redraw, stylize, reconstruct, or approximate any logo, seal, badge, crest, emblem, or wordmark? If yes, reject the image.
- Was any unrequested duplicate branding added in a footer, corner, or decorative area?
- Could any decorative mark reasonably be mistaken for an official organization mark?
- If an authentic asset could not be reproduced exactly, was it omitted rather than approximated?

### Typography
- Poppins?
- Adequate size and contrast?

### Data
- Numbers copied correctly?
- Correct scale?
- Correct benchmark?
- Correct interpretation?

### Terminology
- PoA converted to P+A?
- P+A/DFP/SP defined?

### Metadata
- Source provided or explicitly omitted?
- Date provided or explicitly omitted?

### Photography
- Age appropriate?
- Academically engaged?
- Diverse without stereotyping?

### Claims
- Supported by the data?
- Comparison period stated for superlatives?
- Acceleration used correctly?

### Preliminary data
- Restricted values concealed?

---


## Validation-driven contrast and panel rules

### Regional comparison plotting areas
For RS-02 regional comparison charts, use a **white or very light plotting area** by default.

Reason:
- the locked regional palettes include deep and muted shades that require a light plotting area for reliable contrast;
- LAUSD Green #00602D must not be used directly on navy;
- light plotting areas improve legibility of small labels and comparison lines.

Recommended structure:
- overall slide/background may remain Region South navy;
- chart card header may use navy;
- chart plotting area should be white or very light gray/blue;
- use dark navy text on light plotting areas;
- use the locked regional colors for lines/markers.

### Science green placement
LAUSD Green #00602D:
- use on white/light backgrounds;
- do not place directly on navy;
- do not pair with navy type on the same green field.

If a Science icon is needed on a dark-navy slide, place the green icon inside a white/light circular or rounded container.

### Small text color
Do not use LAUSD Bright Blue #0089FF, LAUSD Orange #FF4D00, LAUSD Gold #FF9C00, or LAUSD Red #FF0000 for text smaller than 17 pt.

For small chart labels, footnotes, and definitions:
- use navy on light backgrounds;
- use white or soft white on dark backgrounds.

---

## Cohort bar treatment

For SBA/CAASPP cohort-change graphics:
- preserve the subject color family as the primary data encoding;
- use bar direction above/below zero to communicate sign;
- use two or more approved shades within the subject family to distinguish favorable/unfavorable or emphasis when needed;
- do not use green/red as the default bar colors for Math or ELA.

Suggested treatments:
- favorable = stronger/brighter subject shade;
- unfavorable = muted/darker subject shade;
- largest gain/decline callouts may use green/red arrows as secondary semantic cues.

The educational meaning of the change must be interpreted correctly; mathematical sign alone does not determine whether a result is favorable.

---

## Approved-example production rule

An "Approved Example" should be finalized in two stages:

1. **Generate/design the composition** using the Region South style rules.
2. **Post-produce brand-critical elements**:
   - insert authentic Region South and/or LAUSD logos only when required by the design or requested by the user;
   - verify that no AI-invented logo, seal, badge, crest, emblem, wordmark, or official-looking substitute mark remains anywhere in the visual;
   - verify that no unrequested duplicate branding was added;
   - verify typography;
   - verify all numeric labels against source data;
   - verify source/date metadata;
   - verify abbreviation definitions;
   - verify embargo restrictions.

Do not designate an AI-generated image as an Approved Example until this post-production check is complete.

## Core AI rule

**Do not improvise brand rules when a Region South standard already exists.**

**An invented or approximated logo is a brand-compliance failure, even if it looks visually appropriate or resembles an official Region South or LAUSD asset.**
