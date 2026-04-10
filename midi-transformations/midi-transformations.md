# MIDI Transformations & Generators

## Overview

MIDI Transformations and Generators allow you to create and modify MIDI patterns quickly.

Transformations modify existing MIDI notes. Generators create new MIDI material.

---

## Accessing MIDI Transformations & Generators

1. Open a MIDI Clip in the Clip View.
2. Select notes in the MIDI Editor (optional for Generators).
3. Right-click inside the MIDI Editor.
4. Choose **Transform** or **Generate** from the context menu.
5. Select the desired tool.

Alternatively:

* Use the **Transform** and **Generate** buttons in the MIDI Editor toolbar.

---

## MIDI Transformations

Transformations modify selected MIDI notes. These tools are useful for evolving patterns and creating variations.

### Available Transformations

#### Velocity Randomize

Randomizes note velocities within a defined range.

**Parameters:**

* Amount — Controls velocity variation range
* Preserve Range — Maintains original velocity boundaries

**Use Case:**
Add a human feel to static MIDI patterns.

---

#### Note Length Adjust

Changes note durations proportionally.

**Parameters:**

* Scale — Multiplies note length
* Minimum Length — Sets lower duration limit

**Use Case:**
Create staccato or legato variations.

---

#### Pitch Shift

Transposes selected notes.

**Parameters:**

* Semitones — Pitch adjustment
* Snap to Scale — Constrains notes to the selected scale

**Use Case:**
Quick harmonic experimentation.

---

## MIDI Generators

Generators create new MIDI patterns automatically.

### Available Generators

#### Rhythm Generator

Creates rhythmic patterns based on density and variation.

**Parameters:**

* Density — Controls note frequency
* Variation — Adds rhythmic variation
* Sync — Aligns to grid

**Use Case:**
Generate drum patterns or rhythmic sequences.

---

#### Melody Generator

Creates melodic sequences using a selected scale.

**Parameters:**

* Scale
* Range
* Complexity
* Step Size

**Use Case:**
Generate melodic ideas quickly.

---

#### Chord Generator

Creates chord progressions within the selected scale.

**Parameters:**

* Scale
* Chord Type
* Complexity
* Rhythm

**Use Case:**
Generate harmonic foundations.

---

## Workflow Example

To generate a melodic idea:

1. Create a MIDI clip.
2. Open the MIDI Editor.
3. Click **Generate**.
4. Select **Melody Generator**.
5. Adjust parameters.
6. Click **Apply**.

Live generates a new MIDI pattern inside the clip.

---

## Tips

* Use Transformations after Generators to refine results
* Combine multiple transformations for variation
* Duplicate clips before experimenting
* Use Undo (Cmd/Ctrl + Z) to revert changes

---

## Notes

* Transformations only affect selected notes
* Generators overwrite the selected region
* Results may vary depending on scale settings

---

## Release Notes Example

* Added MIDI Transformations for modifying note data
* Introduced MIDI Generators for creating new patterns
* Added scale-aware pitch and harmony tools
* Improved MIDI editing workflow with contextual controls
* Added parameter controls for density, variation, and complexity
