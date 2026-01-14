# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is an Obsidian vault named "lee-s-brain" that serves as a personal knowledge management system focused on growth marketing, CRM strategy, and project documentation. It is NOT a traditional software codebase but rather a collection of interconnected markdown notes, canvas files (visual diagrams), and reference materials.

## Structure

The vault follows a modified PARA method organization:

- **1. Project/** - Active project documentation (e.g., "KOSAC 공모전.md")
- **2. Area/** - Areas of responsibility (currently empty)
- **3. Resource/** - Reference materials (currently empty)
- **4. Archive/** - Completed or inactive items (currently empty)

## Key Files and Their Purposes

### Core Framework Documents

- **Growth Marketer Base Camp.md** - Central hub containing a Mermaid diagram that maps the entire growth marketing funnel across 4 stages:
  1. Acquisition (유입 단계) - Traffic and user acquisition
  2. Activation (활성화 단계) - User engagement and onboarding
  3. Revenue (구매 단계) - Conversion and purchase
  4. Retention (재구매 단계) - Customer retention and lifetime value

  Each stage defines: TO DO actions, DELETE items to clean up, DATA metrics to track, CLEAN data hygiene tasks, and DOCS documentation methods.

- **01_Data_Taxonomy.md** - Data definitions and taxonomy documentation (currently empty, referenced in framework)

- **02_CRM_Logic.md** - CRM segmentation and customer journey logic (contains canvas reference to "3일차 리마인드 메시지 안내")

- **03_Growth_Log.md** - Growth experiment log and A/B test documentation (currently empty, referenced in framework)

### Canvas Files (Visual Diagrams)

Canvas files use Obsidian's visual canvas format (JSON-based node-edge diagrams):

- **3일차 리마인드 메시지 안내.canvas** - Detailed CRM messaging flow showing welcome messages and retention campaigns with A/B testing variants, including analysis of competitor approaches (널핏, 비비드, 올리브영, 에이블리, 케이스티파이)

- **바이트 50M 전략.canvas** - Strategic planning for "바이트" brand's 50M goal

- **바이트몰_광고 퍼널.canvas** - Advertising funnel for 바이트몰 (Byte Mall)

### Reference Images

PNG files show competitor welcome message examples (01_널핏_웰컴메시지.png through 05_케이스티파이_웰컴메시지.png) used for CRM benchmarking.

## Working with This Vault

### Markdown Conventions

- Uses Obsidian-flavored markdown with wiki-links: `[[filename|display text]]`
- Mermaid diagrams are embedded using code fences with `mermaid` language identifier
- Internal links connect related documents

### Canvas File Format

Canvas files are JSON structures with:
- `nodes[]` - Visual elements (text boxes, file embeds, groups)
- `edges[]` - Connections between nodes
- Node types: "text", "file", "group"
- Spatial positioning with x, y coordinates
- Color coding for categorization

### Creating New Content

When adding new documentation:
1. Place active projects in "1. Project/"
2. Link related documents using wiki-link syntax
3. Reference the Growth Marketer Base Camp framework for context on where new content fits
4. For CRM flows, consider using canvas format for visual clarity
5. Follow the established naming convention using Korean and English mixed appropriately

### Version Control

- `.gitignore` excludes Obsidian workspace files and system files (.DS_Store)
- Git repository is initialized but currently has no commits
- All content files are untracked and ready for initial commit

## Context for AI Assistance

When asked to work with this vault:
- Understand this is a **knowledge base**, not application code
- Preserve Obsidian markdown syntax and wiki-links
- Maintain the growth marketing framework structure
- Respect the Korean-English bilingual nature of content
- Canvas files should be edited carefully as they have specific JSON structure requirements
- Focus on content organization, linking, and documentation clarity rather than software development concerns
