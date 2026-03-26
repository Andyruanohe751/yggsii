# Yggsii Vision

Yggsii is a story development environment for writers who need to inspect a narrative as a system, not just draft it as a long document.

## Core idea

A story should be navigable from multiple angles at once.

A writer should be able to answer questions like:

- who is in this part of the story
- which characters have met, and how often
- what happens before and after a scene
- where a scene sits in the chapter structure
- whether the emotional and causal timeline still makes sense
- what parts of the manuscript are missing, weak, or contradictory

The app is meant to make narrative structure visible.

## Product thesis

Most writing tools are document-first. They are good at typing, but weak at inspection.

Yggsii should be structure-first and manuscript-aware.

The manuscript still matters, but it should sit inside a richer model that understands scenes, characters, locations, chronology, relationships, and continuity.

The goal is not to replace writing. The goal is to make complex stories coherent enough to write well.

## MVP direction, already established

The current MVP proves the basic shape:

- local-first single-user app
- project, chapter, scene, character, and location entities
- scene-centric editing
- visual timeline surface
- character co-presence and meeting surface
- dark and light modes
- quick, inspectable navigation rather than a blank-page workflow

This is the foundation, not the finish line.

## What Yggsii should become

Over time, Yggsii should evolve into a narrative intelligence workspace with a few strong pillars.

### 1. Story structure as a first-class model

The story should be represented as linked entities rather than loose notes.

Likely model growth:

- projects
- arcs
- chapters
- scenes
- beats or events
- characters
- relationships
- factions or groups
- locations
- items, motifs, or lore entities
- timeline entries and constraints
- notes, tags, and references

Scenes remain the central operating unit, but they should connect outward into everything else.

### 2. Visual inspection modes

The app should let the writer see the story from different perspectives without breaking context.

Likely views:

- timeline view, chronological and optionally story-order
- character interaction graph
- location occupancy and movement view
- chapter and pacing view
- relationship map
- unresolved thread tracker
- continuity warnings and dependency chains

The key principle is that visualisation is not decoration. It is a debugging surface for fiction.

### 3. Coherent time handling

The current manual ordering is enough for MVP, but the longer-term system should support richer chronology.

Future capabilities may include:

- absolute or relative time markers
- parallel events
- flashbacks and non-linear narrative order
- duration and travel assumptions
- age and availability constraints for characters
- continuity checks for impossible overlaps

Writers should be able to distinguish story order from chronological order.

### 4. Character and relationship intelligence

Characters should not just be names attached to scenes.

Eventually Yggsii should help track:

- appearances and absences
- introductions
- relationship changes over time
- alliances, conflicts, and secrets
- viewpoint distribution
- character goals and pressure points
- who knows what, and when

This is where the tool starts becoming genuinely useful for large casts.

### 5. Manuscript integration without losing structure

The app should still support drafting, but in a way that stays connected to the model.

Desired direction:

- structured scene drafts
- manuscript compilation from scene order
- scene notes versus prose separation
- revision status and draft states
- export to common writing formats
- import from existing manuscript structures where practical

The writer should never have to choose between structure and prose.

### 6. Local-first, then syncable

The product should remain local-first in spirit.

That means:

- fast startup
- useful offline
- no backend dependency for the core writing loop
- durable local data model

Later, sync and collaboration can exist, but they should not undermine the local writing experience.

### 7. Taste and usability

The interface should feel calm, deliberate, and writer-friendly.

Important qualities:

- dark and light mode from the start
- dense enough for power users, not visually chaotic
- inspectable at a glance
- low-friction editing
- minimal ceremony for common actions
- visual clarity over ornamental UI

## Near-term roadmap

After the MVP, the most valuable next steps look like this:

1. Import and export, so projects are portable.
2. Safer editing flows, including delete support and better validation.
3. Richer timeline semantics, beyond manual ordering.
4. Better relationship modelling between characters.
5. A clearer manuscript assembly view.
6. Persistence upgrades beyond raw localStorage.
7. Search, filters, and tags for larger projects.

## Non-goals, for now

To keep the project coherent, these should stay out until the core loop is stronger:

- multiplayer collaboration
- cloud-first architecture
- heavy AI features as a crutch for weak data modelling
- flashy graph views without real narrative utility
- a full publishing pipeline

## Design rule

Every feature should make the story easier to inspect, reason about, and keep coherent.

If a feature only makes the app look more sophisticated, but does not help a writer think, it is probably noise.

## Current record

The practical MVP summary lives in `README.md`.

This file exists to preserve the larger direction, so future resets do not collapse the project back into just the current implementation.
