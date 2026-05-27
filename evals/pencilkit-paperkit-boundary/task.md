# Document Markup Framework Boundary

## Problem/Feature Description

A document editor is planning an iOS 26 annotation mode. Users need freehand Apple Pencil notes and signatures, but the same mode also needs shapes, arrows, text boxes, imported images, stickers, and a system-standard markup toolbar. The team is unsure whether to build on a raw PencilKit canvas, a PaperKit surface, or a combination.

Write the framework boundary and a smallest useful code sketch for the recommended approach. The answer should help engineers avoid rebuilding platform markup behavior by hand while still understanding where PencilKit fits.

## Output Specification

Create `markup-framework-boundary.md` containing:

- The recommended owner framework for this feature.
- The parts that still belong to PencilKit.
- A minimal UIKit or SwiftUI-oriented code sketch.
- Notes on preserving existing freehand drawing data if the app already has PencilKit content.

Do not create an Xcode project. Keep the output to implementation guidance and snippets.
