# Muthoot Finance Branch Locator — Deployment Guide

Built from: Branch Master Sheet, 10 June 2026 (shared by Garima Sharma)

## What's in this folder
- index.html — the Branch Locator tool (design matched to the current site)
- data.js — all branch data (MFL: 2,079 | MML: 1,017 | South: 3,297 after removing 1,812 duplicates already present in MFL)

## Option A — Update the existing site (easiest)
The current locator lives at nishantnarendra.github.io/Muthoot/, which is on
Nishant Sir's GitHub account. Send him both files and ask him to:
1. Open github.com and go to his repository named "branch-locator"
2. Click "Add file" → "Upload files"
3. Drag both index.html and data.js in (this replaces the old ones)
4. Click "Commit changes"
The live site updates automatically within 1–2 minutes. Nothing else needed.

## Option B — Host it on your own GitHub account
1. Go to github.com and click Sign up (free) — use your work email
2. After signing in, click the "+" (top right) → "New repository"
3. Name it: branch-locator → tick "Public" → Create repository
4. Click "uploading an existing file" → drag in index.html and data.js → Commit
5. Go to Settings → Pages (left sidebar)
6. Under "Branch", choose "main" and "/ (root)" → Save
7. Wait 2 minutes. Your site will be live at:
   https://YOUR-USERNAME.github.io/branch-locator/

## Updating data next month
When Garima shares a new Branch Master Sheet, just ask Claude to regenerate
data.js from the new file and re-upload only data.js. The index.html stays
the same.
