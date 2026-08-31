---
name: creating-general-video-covers
description: Use when a user wants to create, generate, design, or produce a video cover/thumbnail for short-form or long-form video platforms, whether they explicitly name this skill or use natural-language requests such as “生成视频封面”, “做个视频封面”, or “帮我设计封面”.
---

# Creating General Video Covers

## Overview

A generic, shareable workflow for creating video covers across industries and platforms.

Core rule:

**Decide first, design second; optimize aesthetics before generation.**

Do not bind this skill to any specific account, person, industry, product, brand, visual identity, or historical project unless the user explicitly provides that context in the current task.

---

## Triggering

Use this skill when the user explicitly invokes `creating-general-video-covers` or clearly asks to create a video cover/thumbnail, including natural-language requests such as:

- 生成视频封面
- 做一个视频封面
- 帮我设计封面
- 根据这个主题做封面
- 给这个视频做封面
- 做抖音/小红书/视频号/YouTube封面

Do not automatically enter the full generation workflow for advisory-only questions such as:

- 视频封面怎么设计？
- 什么封面点击率高？
- 这个标题适不适合做封面？

Those should be answered as consultation unless the user also asks to create the cover.

---

# Mandatory Workflow

The workflow order is fixed:

1. Understand the task and assets
2. Generate title options
3. User confirms title
4. Confirm person usage
5. Present 3 clearly different visual styles
6. User selects a style
7. Perform Taste-style aesthetic reduction/optimization
8. Present final pre-generation plan
9. User confirms generation
10. Generate both 3:4 and 4:3 versions
11. Inspect both versions
12. Task is complete only when both versions pass inspection

Do not skip ahead.

---

# Step 1 — Understand the Task

Identify, when provided:

- Platform
- Video topic
- Script
- Reference/template image
- Person reference image
- Product or subject image
- Brand assets
- Logo
- Visual preferences
- Explicit constraints

If no template/reference image is provided, use an original design direction.

If a reference image is provided, extract design logic such as:

- Composition
- Information hierarchy
- Subject scale
- Typography behavior
- Color relationships
- Negative space
- Visual rhythm

Do not mechanically copy the reference.

---

# Step 2 — Title First

Before any image generation, produce title options only.

Each option should contain:

- Main title
- Subtitle

Recommended default ranges:

- Main title: 4–10 Chinese characters
- Subtitle: 6–14 Chinese characters

The cover should normally contain only:

**1 main title + 1 subtitle**

Do not turn the cover into a script summary or information poster.

Do not generate images before the user confirms the title.

---

# Step 3 — Person Confirmation

## If a person reference image is provided

Confirm whether the person should appear in the cover.

If yes, preserve identity-relevant traits as closely as possible, including:

- Facial features
- Hair
- Apparent age
- Skin tone
- Gender presentation
- Distinctive appearance traits

Pose, expression, crop, and placement may change to fit the topic.

## If no person reference image is provided

You MUST ask whether the user wants a person in the cover.

Offer these choices:

1. No person — use text + product/subject/scene
2. Generic person — non-user, non-fixed-IP presenter/model
3. Wait for user to upload a person reference image

Until the user chooses, do not generate a person.

Never import a person from previous tasks, accounts, brands, or unrelated projects.

---

# Step 4 — Present 3 Clearly Different Visual Styles

After title and person decisions are confirmed, present exactly 3 distinct visual directions.

Each direction should include:

- Style name
- Core visual idea
- Composition logic
- Visual language
- Why it fits the topic

The 3 styles must differ meaningfully in at least two dimensions such as:

- Composition
- Subject scale
- Typography
- Color system
- Information hierarchy
- Camera angle
- Scene treatment
- Mood
- Graphic language
- Use of negative space

Changing only colors does not count as three different styles.

Do not generate images until the user selects one.

---

# Step 5 — Taste-Style Aesthetic Optimization

After the user selects a style, perform an aesthetic reduction pass before generation.

The goal is not to add more decoration. The goal is to remove unnecessary complexity.

## Information Density

Check for and remove unnecessary:

- Extra headlines
- Small text
- Process diagrams
- Checklists
- Material lists
- Repeated badges
- Multiple warning boxes
- Excessive icons
- Third or fourth text messages

If the cover feels crowded, delete first instead of rearranging everything.

## Visual Focus

There must be one clear first focal point.

Default hierarchy:

**Main title > core subject > subtitle > supporting elements**

Do not let text, person, product, icons, warnings, and logos all compete equally.

## Negative Space

Do not fill empty space simply because it exists.

Preserve breathing room around:

- Main title
- Subject
- Important edges
- Thumbnail-safe areas

## Typography

Use 1–2 major typographic states by default.

Avoid:

- Too many typefaces
- Excessive outlines
- Excessive shadows
- Multiple gradient text treatments
- Unnecessary 3D effects

## Color

Prefer:

**Primary color + supporting color + accent color**

Use accent colors selectively.

## Reduce AI-Poster Look

Actively avoid excessive:

- HDR
- Over-sharpening
- Glows
- Speed lines
- Explosive stickers
- UI-like cards
- Warning labels
- White cutout outlines
- Decorative micro-elements

High clickability does not mean visual overload.

---

# Step 6 — Final Pre-Generation Plan

Before generation, present a concise execution plan:

## Title
- Main title:
- Subtitle:

## Person
- Yes / No
- If yes: placement, pose, expression

## Core Subject
- Main visual subject

## Composition
- Main spatial relationship

## Visual System
- Style
- Primary color
- Accent color
- Background treatment

## Explicit Exclusions
- List what will intentionally NOT appear

If the user has already clearly said “确认生成”, “生成”, “可以”, or equivalent, do not ask for redundant confirmation.

---

# Step 7 — Generation Rules

Once generation is confirmed, generate both versions automatically:

- **3:4 vertical**
- **4:3 horizontal**

This is mandatory.

The user should not need to ask for the second ratio.

Do not treat one successful image as task completion.

---

# Dual-Ratio Rules

The two versions must preserve:

- Main title
- Subtitle
- Core subject
- Visual style
- Color system
- Person identity/settings if used
- Overall theme

But they must be recomposed independently.

Do NOT simply crop one image into the other ratio.

## 3:4 Vertical

Prefer:

- Strong vertical hierarchy
- Top/bottom structure
- Concentrated subject placement
- Mobile-feed readability

## 4:3 Horizontal

Prefer:

- Left/right relationships
- Wider environmental context
- More lateral breathing room
- Horizontal balance

---

# No Unnecessary Pausing

Only pause for user input when a real decision is required:

1. Title selection
2. Person selection
3. Visual style selection
4. Final generation confirmation

Do not pause merely because:

- A tool call took time
- One image finished
- A sub-step completed
- The task is complex
- The user took time to reply
- An intermediate explanation was given

If the user asks a side question during the workflow:

1. Answer the question
2. Preserve the current workflow state
3. Continue from the same stage

Do not restart the workflow unless the user explicitly asks to restart.

---

# Fact Accuracy Rule

If the cover topic contains potentially regulated, factual, legal, medical, financial, statistical, policy, time-sensitive, or official claims, verify the core claim before turning it into an absolute headline when verification is needed.

If the user’s source wording appears uncertain or potentially inaccurate:

- Flag the issue
- Suggest a safer/accurate formulation
- Do not amplify uncertain wording merely for click-through rate

The cover title may simplify the script, but should not distort the underlying facts.

---

# Post-Generation Inspection

Inspect BOTH 3:4 and 4:3 versions separately.

## Text

Check:

- Main title accuracy
- Subtitle accuracy
- Typos
- Garbled characters
- Unapproved extra text

## Person (if present)

Check:

- Face consistency
- Eyes
- Hands
- Fingers
- Arms
- Skin tone
- Hair
- Teeth
- Body proportions
- Intersections / clipping

## Subject

Check for structural or semantic errors relevant to the subject category.

Examples include:

- Product shape/count/packaging
- Vehicle body/wheels/lights/windows
- Food geometry and serving logic
- Device/product proportions
- Landmark recognizability

## Composition

Check:

- Text clipping
- Safe-area violations
- Subject clipping
- Overlap between text and subject
- Balance
- Thumbnail readability

## Aesthetic Recheck

Ask:

**If removing an element makes the cover better, should that element have been there at all?**

Remove unnecessary elements when possible.

---

# Information Density Hard Rule

By default, the cover body contains only:

**Main title + subtitle**

Elements that require explicit justification before inclusion:

- Logo
- Badges
- Small labels
- Data callouts
- Process steps
- Checklists
- Material lists
- Icons
- Third text message

“Empty space” is not justification for adding content.

---

# Generic-Skill Isolation Rule

This skill must remain generic.

Do not import from historical context unless the user explicitly supplies or requests it in the current task:

- Previous account identities
- Previous people
- Previous brands
- Previous products
- Previous industries
- Previous visual systems
- Previous logos
- Previous templates

Current-task explicit instructions take priority over any historical preference.

---

# Completion Definition

The task is complete only when:

- 3:4 version has been generated
- 4:3 version has been generated
- Both versions have been checked

If only one ratio exists, the task is not complete.

---

# Quick Reference

**Trigger → Title → Person → 3 Styles → Taste → Final Plan → Confirm → 3:4 + 4:3 → Inspect Both**

---

# Common Mistakes

- Generating immediately after receiving the topic
- Adding a person without confirmation
- Reusing a person from unrelated prior work
- Treating color swaps as three different styles
- Turning the cover into an information poster
- Skipping aesthetic reduction
- Pausing after one image
- Generating only one ratio
- Cropping one image into both ratios
- Adding unapproved logos, claims, labels, or text
- Importing historical brand/industry context into a generic task
