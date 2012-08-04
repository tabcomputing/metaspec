# Universal Metadata Specifications

## Introduction

Metaspec is a system for the standardization of project metadata.

## Specifications

All specification must be concrete, that is to say they
can not have optional characterisitcs. A field has one and
only one name, and one and only one structure.

All metadata files are stored as YAML. JSON can be used becuase
it is a subset of YAML, but all metadata parsers must support
YAML.

All metadata files are stored in the .meta directory of a project's
root directory.

