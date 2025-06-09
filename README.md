
# 🌿 Image Optimization Agent

## Overview

The GitHub Sustainability Team is exploring ways to **green software at scale**. As part of this, we’ve identified a promising deployment mechanism: **AI Agents** that autonomously reduce the carbon and energy footprint of software.

This Proof of Concept (PoC) introduces the **Image Optimization Agent**—an AI-powered workflow that converts & compresses large images in code repositories to cut emissions and improve performance.

## Purpose

Large images consume energy throughout their lifecycle—during development, storage, deployment, and when accessed by users. Optimizing them has measurable sustainability and performance benefits:

* 💾 **Reduced storage and bandwidth**
* 🌐 **Lower data transfer and server energy usage**
* ⚡ **Less energy used on end-user devices**
* 🚀 **Faster page loads, better UX, and improved SEO**

Reference: [Web Sustainability Guidelines – Optimize Images](https://w3c.github.io/sustainableweb-wsg/#all-images-must-be-optimized-for-sustainability)

## How It Works

1. A developer opens a GitHub Issue using the provided prompt template.
2. The issue is assigned to **GitHub Copilot** (Ensure it has permissions to access the repo!).
3. Copilot analyzes the repository, compresses the images, and automatically opens a Pull Request with the optimized assets.

## What's in the Repo

* 🧠 **Prompt In Issue Template Format** – The text that drives the Copilot Agent’s behavior
* 🖼️ **Example Outcome** – Shows a sample review of images in the repo and a PR with compressed images

## Next Steps

We're exploring scaling and sharing this tool:

* ✅ Pilot on a friendly project with a larger image set
* 📈 Collaborate with bigger teams to test impact at scale
* 📣 Promote to wider dev audiences as a sustainability best practice
