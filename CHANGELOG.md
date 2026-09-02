# Changelog

All notable changes to this specification are recorded here. This project uses
semantic versioning.

## [1.0.2] - 2026-09-02

- PDF edition re-rendered. The SPEC.pdf shipped in 1.0.1 was a one-page browser error
  page produced by a rendering race; the text of the specification did not change.

## [1.0.1] - 2026-09-02

Corrections. No change to the outline definition.

- Certificate term corrected to hexagonal modified brilliant, the wording on an
  IGI report for a Stienhardt Dutch Marquise (LG799689559, 2026-05-09). The
  earlier "modified marquise brilliant" was wrong.
- Faceting resolved: the Dutch Marquise is cut for brilliance; the Elongated
  Hexagon is the step cut that shares the outline. Placeholders removed.
- Length-to-width: the unsupported "typical 1.5 to 1.9" range and the "default
  1.6 to 1.75" claim are withdrawn. The specification now publishes measured
  values only (reference stone 1.84) and explains how to compute the ratio.
- Durability wording replaced with standard setting practice for pointed ends.
- Craft claim stated as it is: Stienhardt controls this cut through a specialized
  factory relationship and hand-sets and finishes the stones in New York City.
  The earlier "cuts these stones in-house" is withdrawn.
- Publisher name is Stienhardt. Repository URLs corrected to
  github.com/JacobiusMakes/dutch-marquise-spec. PDF edition added (SPEC.pdf).

## [1.0.0] - 2026-06-16

First public release.

- Normative definition of the Dutch Marquise cut (elongated hexagon, angular
  points along the long edges tapering toward each end, trade name, certificate
  term modified marquise brilliant, length-to-width 1.5 to 1.9, Stienhardt
  default 1.6 to 1.75). Faceting is held pending founder confirmation
  (crushed-ice vs step-cut).
- Companion definition of the French Marquise (pointed marquise with French
  tips, certificate term marquise brilliant).
- JSON Schema for a structured diamond-cut definition record.
- Machine-readable data records for both cuts, each claim sourced.
- schema.org DefinedTerm and Dataset JSON-LD for web embedding.
- Explicit scope and claim boundary: Stienhardt publishes this plain, repeatable
  definition and cuts these stones in-house, and never claims to have invented,
  patented, or trademarked the term.
