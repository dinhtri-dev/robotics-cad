# Robotics CAD Archive

Year2 source archive by dinhtri-dev. Original workspace files are unchanged.

## Contents and status

robot-arm and robot-fish retain design variants and assembly dependencies. CAD geometry, absolute references and manufacture readiness have not been validated in Inventor. Duplicate part files required by assemblies are retained; Git deduplicates identical blob contents. Research PDFs, backups, tool templates and ZIP copies are excluded.

## Run / inspect

Open native .iam/.ipt with compatible Autodesk Inventor. STEP/STL exports can be used by compatible CAD viewers. Use the file inventory to distinguish versions rather than assume the newest name is final.

Install only this project's listed dependencies in a separate virtual environment. Model binaries, large datasets, private configuration and generated output are excluded. Check DATA_AND_MODELS.md when present.

## Archive validation

See ARCHIVE_STATUS.md and SECURITY_REVIEW.md for the exact publication scope, tests and remaining limitations. A successful source-archive check does not certify production deployment, firmware flashing, model accuracy or CAD geometry.

## Future work

The consolidated Google document records project-specific fixes, missing functions and suggested features. This commit focuses on reproducible archiving, not implementing that roadmap.

## Directory guide

- `robot-arm`
- `robot-fish`

## Tests actually run

File types, sizes and checksums inspected. Native CAD assemblies and geometry have not been opened or manufactured.
