# Design Rules

## 01. TYPOGRAPHY SYSTEM

### FONT SIZE SYSTEM (px)

10 / 12 / 14 / 16 / 18 / 20 / 24 / 30 / 36 / 44 / 52 / 62 / 74 / 86 / 98

**Default font size:** 16px

#### Font Weights:

- Default: 400
- 100
- 300
- 400
- 700
- 900

#### Line Heights:

- Slightly tight: 1.2
- Default: 1.5
- Generous spacing: 1.6

#### Letter Spacing

**Tight Letter Spacing**

- `-0.01rem` (equivalent to `-0.1px`):

  - **Use For**: Headings or titles where you want a more compact look.
  - **Note**: Creates a tighter appearance, best used sparingly to avoid readability issues.

- `-0.005rem` (equivalent to `-0.05px`):
  - **Use For**: Subheadings or smaller text elements that need a slightly condensed look.
  - **Note**: Subtle tightening of text, good for maintaining readability while saving space.

**Normal Letter Spacing (default)**

- `0rem`:
  - **Use For**: Default letter spacing, suitable for most body text and elements.
  - **Note**: Maintains the default spacing of the font, ensuring optimal readability.

**Loose Letter Spacing**

- `0.005rem` (equivalent to `0.05px`):

  - **Use For**: Paragraph text or content areas where readability is a priority.
  - **Note**: Slightly increases spacing, enhancing readability without creating too much space.

- `0.01rem` (equivalent to `0.1px`):

  - **Use For**: Uppercase text or elements where additional spacing can improve clarity.
  - **Note**: Provides a noticeable but not excessive increase in spacing, suitable for uppercase or emphasis.

- `0.02rem` (equivalent to `0.2px`):

  - **Use For**: Special emphasis or decorative text where readability is not the primary concern.
  - **Note**: Significantly increases spacing, use for stylized text elements or highlights.

- `0.03rem` (equivalent to `0.3px`):
  - **Use For**: Large displays, banners, or decorative headings.
  - **Note**: Creates very loose spacing, best used in designs where text density is low, and visual impact is desired.

## 02. WHITESPACE

2 / 4 / 8 / 12 / 16 / 24 / 32 / 40 / 48 / 56 / 64 / 80 / 96 / 112 / 128 / 144 / 160 / 176 / 192 / 208 / 224 / 240 / 256

**Note**: 1140px or 1200px are standard widths of a browser viewport. We can use 1440px for the container if the browser viewport is 1920px or larger.

## 03. COLOURS

- **Colors**
- **Tints**

## 04. IMAGES

- **Height:**
- **Width:**

## 05. ICONS

## 06. LOGO

- **Height:**
- **Width:**

## 07. SHADOWS

### BUTTONS

- **Static:**
  - `box-shadow: 0 1rem 1.5rem rgba($color-black, 0.10);`
- **Hover:**
  - `box-shadow: 0 1rem 2rem rgba($color-black, 0.15);`
- **Active:**
  - `box-shadow: 0 0.5rem 1rem rgba($color-black, 0.15);`

### IMAGES

- `box-shadow: 0 2.4rem 4rem rgba($color-black, 0.4);`
- **Hover:**
  - `box-shadow: 0 1.6rem 3.2rem rgba($color-black, 0.5);`

### CARDS

- `box-shadow: 0 1.6rem 4rem rgba($color-black, 0.15);`

### INPUT FIELDS

- **Focus:**
  - `box-shadow: 0 1rem 2rem rgba($color-black, 0.15);`

## 08. BORDER-RADIUS
