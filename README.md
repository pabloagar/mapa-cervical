# Mapa cervical

**English** · [Leer en español](README.es.md)

**An editable neck anatomy diagram, from annotations to an A4 printout.**

A graphical editor prototype for documenting findings on a neck anatomy diagram. It supports drawings, text and arrows, saving an editable study and preparing a printable output.

[Explore the editor](https://mapa-cervical-salvador.pablo-aguirre.chatgpt.site)

<img src="assets/mobile.png" alt="Mapa cervical annotation tools and neck anatomy diagram in a mobile browser viewport, without patient data" width="320">

*Mobile browser capture with no patient data. The app interface is in Spanish.*

## The problem

Paper diagrams help communicate the location of a finding, but correcting an annotation or revisiting a study can require redrawing part of the document. This project explores how to preserve that visual approach while making its elements editable.

## What it does

- Draw freehand strokes, ellipses, contours and lines.
- Add text and arrows to the diagram.
- Select, move, resize and rotate drawings.
- Adjust colors, stroke width and fill transparency.
- Undo and redo changes.
- Save and reopen an editable study.
- Prepare an A4 page for printing or saving as PDF through the browser.

## Status and scope

A working graphical documentation prototype. The user creates the annotations: the editor does not interpret images or determine clinical staging automatically. Its use in a clinical workflow awaits evaluation.

## My contribution

**Dr. Pablo Aguirre Araya, physician in Chile's MGZ public service program, Arica.** Identifying the need, defining the annotation workflow and making design decisions, with iterative AI-assisted development.

## Storage and data

The editor uses browser storage to recover work and lets users download an editable copy. Browser storage can be lost when site data is cleared; keeping the downloaded copy is advisable.

Explore the demo using fictional examples without patient identifiers. The demo is not an institutional health record system or study repository.

## Technology

HTML, CSS and JavaScript, with SVG elements for annotations. Printing uses the browser's built-in options.

## Next steps

- Observe professional use and review the clarity of the tools.
- Evaluate print legibility and study recovery.
- Review the provenance and permissions of anatomical assets before distributing a code and asset package.

[Open the demo](https://mapa-cervical-salvador.pablo-aguirre.chatgpt.site) · [Contact](mailto:pablo.aguirre.araya@gmail.com)
